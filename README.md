# BT-2023

## Afbeeldingen
![image](https://user-images.githubusercontent.com/94360732/227063105-e9eb1221-cf0c-4896-b290-d3d9136b5123.png)

Stel je voor je hebt een website vol afbeeldingen, maar je hebt een hele slechte internet. Hoe zie je dan de afbeeldingen? Worden ze überhaupt geladen? Als ze niet worden geladen wat zie je dan?
Hoe kunnen wij nou afbeeldingen zo toegankelijk mogelijk maken voor elke gebruiker? Hoe kunnen wij de afbeelding laten zien wanneer er trage internet is,  een andere device wordt gebruikt dat niet verschillende afbeelding formaten ondersteund of als de gebruiker blind/ slechtziend is, hoe geven we de informatie mee? 

Nou dan hebben we te maken met de developingsmethode progressive enhancement. 
Een progressive enhancement bij de afbeeldingen kan zijn dat je een versie van de afbeelding met een lage resolutie standaard gebruikt en een versie met een  hogere resolutie die wordt geladen voor gebruikers met apparaten of browsers die dit ondersteunen.

Er zijn verschillende manieren hoe je de afbeeldingen toegankelijk voor iedereen kan maken, dat zijn:
- Het "alt"-attribuut te gebruiken. Als de afbeeldingen niet worden geladen, kun je de alt text weergeven (waar er een beschrijving van de afbeelding staat). Ook is dit heel fijn voor de screenreader voor mensen die beperkte zicht hebben. Zij zien de afbeelding niet, maar de afbeelding kan dmv een alt text beschreven worden. 
- Lazy Loading.  Even terug op de trage internetverbinding,  Als de gebruiker een trage internetverbinding heeft, duurt het wat langer voor het laden van de content. De content wordt in een keer geladen, waardoor het wat lang kan gebeuren. Hoe kan je dit nou voorkomen? LAZY LOADING to the rescue!! Lazy loading is een methode die je in je js kan toepassen. Door lazy loading kan je het laden van de afbeelding uitstellen totdat ze echt nodig zijn. Door Lazy Loading kan de laadtijd wat vermindert worden en de hoeveelheid gegevens verminderen die gedownload moet worden. 
![image](https://user-images.githubusercontent.com/94360732/227063053-ed9a4b6d-b376-41b9-aca3-76dedcf19980.png)

- Responsive afbeelding.  Door het responsive maken van de afbeelding wordt de grootte en het formaat van de afbeeldingen aangepast op basis van het apparaat en de schermgrootte van de gebruiker. Dit kan ervoor zorgen dat afbeeldingen correct wordt weergegeven op alle apparaten en kan ook de hoeveelheid gegevens die moet worden gedownload verminderen.
![image](https://user-images.githubusercontent.com/94360732/227063301-ea7511bc-2ec1-4765-9f3e-9eb5737b270e.png)


## custom fonts
![image](https://user-images.githubusercontent.com/94360732/227063002-b4a93b11-ea55-4327-9c5d-ce0301310517.png)

Niet iedereen heeft dezelfde soort set fonts, zeker niet als je custom fonts gebruikt. De gebruiker kan dan bijvoorbeeld de tekst niet zien, omdat  ze de specifieke fonts niet hebben. Hoe kunnen wij met progressive enhancement dit veranderen?

Als je het custom fonts gebruikt is het handig om gebruik van een fallback font te maken. Zo kan je met een fallback font gebruiken die op alle apparaten en browsers te zien is en beschikbaar is. 
Zo wordt de custom font automatisch vervangen wanneer de gebruiker een custom font heeft die niet wordt ondersteund door de browser. 
![image](https://user-images.githubusercontent.com/94360732/227063418-b272797d-93bd-44d9-8dbd-6239c5a2f474.png)

Er zijn verschillende manieren hoe je een custom font toegankelijk voor iedereen kan maken, dat zijn:
- @font-face in css. @font-face is een CSS-regel waarmee jouw custom font kunt invoeren om op een website te verschijnen, zelfs als het specifieke lettertype niet op de computer van de bezoeker is geïnstalleerd. Zorg ervoor dat je  zowel het fondsbestand als de fontsformaten (bijv. WOFF, TTF, EOT) benoemt om ervoor te zorgen dat het te zien is bij zoveel mogelijk apparaten en browsers.
- Font-family in css. Font-family kan gebruikt worden om zowel het aangepaste font als het fallback font op te geven. Dit zorgt ervoor dat het fallback-lettertype wordt weergegeven op apparaten en browsers die het aangepaste lettertype niet ondersteunen.
- Function detection. Voorbeelden hiervan zijn Modernizr of CSS @supports, door deze code kan je controleren of de browser van de gebruiker het custom font ondersteunt voordat het wordt geladen. Als de browser het lettertype niet ondersteunt, wordt in plaats daarvan het fallback-lettertype gebruikt
