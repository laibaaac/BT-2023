# BT-2023

## Afbeelding 
Progressive enhancement is een webdevelopings techniek waarbij wordt begonnen met een eenvoudige, functionele versie van een webpagina en vervolgens meer geavanceerde functies worden toegevoegd voor gebruikers met meer geschikte apparaten of browsers.

In de context van afbeeldingen houdt progressieve verbetering meestal in dat een versie met een lage resolutie van een afbeelding als standaard wordt gebruikt en vervolgens een versie met een hogere resolutie wordt geladen voor gebruikers met apparaten of browsers die dit ondersteunen.

Deze aanpak heeft verschillende voordelen, waaronder:

Snellere laadtijden voor gebruikers met langzamere verbindingen of minder capabele apparaten, die mogelijk geen grote afbeeldingsbestanden aankunnen.

Verbeterde toegankelijkheid voor gebruikers met een handicap, die mogelijk ondersteunende technologieën gebruiken die geen grote afbeeldingsbestanden aankunnen.

Verbeterde zoekmachineoptimalisatie (SEO), omdat zoekmachines gemakkelijker kleinere afbeeldingsbestanden kunnen crawlen en indexeren.

Verbeterde algemene gebruikerservaring, aangezien gebruikers nog steeds toegang hebben tot de basisinhoud van de pagina, zelfs als ze de afbeeldingen met hoge resolutie niet kunnen bekijken.

Over het algemeen is progressieve verbetering een krachtige tool voor webontwikkelaars die websites willen maken die toegankelijk, efficiënt en gebruiksvriendelijk zijn

## custom fonts uitzetten
Aangepaste lettertypen kunnen ook worden geïmplementeerd met behulp van progressieve verbetering. Bij het gebruik van aangepaste lettertypen is de standaardbenadering het gebruik van een terugvallettertype dat beschikbaar is op alle apparaten en browsers, en vervolgens het aangepaste lettertype te laden voor gebruikers met apparaten of browsers die dit ondersteunen.

Hier zijn enkele van de stappen die betrokken zijn bij het implementeren van aangepaste lettertypen met progressieve verbetering:

Kies een fallback-lettertype dat qua stijl vergelijkbaar is met uw aangepaste lettertype. Dit zorgt ervoor dat uw tekst leesbaar blijft, zelfs als het aangepaste lettertype niet kan worden geladen.

Gebruik de @font-face-regel in uw CSS om het aangepaste lettertype te laden. Zorg ervoor dat u zowel het lettertypebestand als de lettertypeformaten (bijv. WOFF, TTF, EOT) opneemt om ervoor te zorgen dat het compatibel is met zoveel mogelijk apparaten en browsers.

Gebruik de eigenschap font-family in uw CSS om zowel het aangepaste lettertype als het fallback-lettertype op te geven. Dit zorgt ervoor dat het fallback-lettertype wordt weergegeven op apparaten en browsers die het aangepaste lettertype niet ondersteunen.

Gebruik functiedetectietechnieken, zoals Modernizr of CSS @supports, om te controleren of de browser van de gebruiker het aangepaste lettertype ondersteunt voordat het wordt geladen. Als de browser het lettertype niet ondersteunt, wordt in plaats daarvan het fallback-lettertype gebruikt.

Door technieken voor progressieve verbetering te gebruiken, kunt u ervoor zorgen dat uw website toegankelijk en functioneel is voor alle gebruikers, ongeacht hun apparaat- of browsermogelijkheden.

