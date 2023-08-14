---
title: Autodesk Docs - Mappenstructuur
date: 2023-08-09T07:05:33.862Z
permalink: /autodesk-docs-mappenstructuur.html
eleventyNavigation:
  order: 0
  key: Autodesk Docs - Mappenstructuur
  parent: Extern
---
Het Autodesk Docs project beschikt over een voorgedefinieerde mappenstructuur.  Deze werd uitgewerkt door de Stad Gent en de BIM-procesmanager.

**Met uitzondering van de mappen in "01_WIP" is de mappenstructuur volledig vast.  Deze mag niet verder uitgebreid worden.**

![](/content/images/mappenstructuur-wip.png)

De mappenstructuur is gebaseerd op de ISO 19650 standaard, en moet als volgt gebruikt worden:

### 00_Referentiebestanden

Bevat alle BIM-gerelateerde referentiebestanden.  Denk aan het BIM-protocol en BIM-uitvoeringsplan, de LOI tabellen, de tekenafspraken van de Stad Gent, ...

### 01_WIP

Is de **W**ork **I**n **P**rogress map.  Elke projectpartner beschikt in deze map over een eigen submap.  In deze map worden de bestanden geplaatst waaraan gewerkt wordt (interne keuken), maar die nog niet geschikt zijn om met andere projectpartners te delen.  Elke projectpartner heeft enkel toegang tot zijn eigen WIP map.

In deze map mogen als enige map in het volledige project eigen submappen aangemaakt worden.

![](/content/images/mappenstructuur-wip-map.png)

### 02_Shared

Ook hier beschikt elke projectpartner over een eigen submap.  In deze map worden de bestanden geplaatst die geschikt zijn om te delen met andere projectpartners.  Alle projectpartners hebben toegang tot alle "shared" mappen.  Je deelt dus met iedereen, niet met één bepaalde projectpartner.

![](/content/images/mappenstructuur-shared-map.png)

### 03_Shared owner

Hier beschikken een beperkt aantal projectpartners over een eigen submap.  Enkel de projectpartners die een rechtstreeks contract met de opdrachtgever (Stad Gent) hebben.  Niet de projectpartners die als onderaannemer voor een andere projectpartner werken.

Bedoeling van deze map is om bestanden uitsluitend met de opdrachtgever te delen.  Denk aan vertrouwelijke informatie: contracten, juridische of financiële documenten, ...

![](/content/images/mappenstructuur-shared-owner-map.png)

### 04_Published

In deze map wordt er qua submappen een andere logica gevolgd.  Hier is er voor elke projectfase een submap voorzien.  Bedoeling van deze map is om "definitieve" bestanden te publiceren: de bestanden die opgeleverd moeten worden bij het einde van een projectfase.

![](/content/images/mappenstructuur-published-map.png)

### 05_Archived

Bestanden die niet meer nodig zijn voor het project kunnen naar deze map verplaatst worden.

Normaalgezien is het gebruik van deze map niet nodig.  Bestanden kunnen ook "verwijderd" worden via de ingebouwde Autodesk Docs  functionaliteiten, en komen zo in een speciale map "verwijderde items" terecht.

![](/content/images/mappenstructuur-verwijderde-items.png)

## Tip: abonneren op map

Wanneer je verwacht dat er in een bepaalde map documenten terecht zullen komen die belangrijk voor je zijn, kan je je op deze map abonneren.  Dit zorgt ervoor dat je een e-mail ontvangt, telkens er iemand een bestand in deze map plaatst.

Bijvoorbeeld: als studiebureau technieken wil je een e-mailbericht krijgen zodra de architect nieuwe informatie in de "02_Shared\02_ONT-ARB_Architectenbureau" map plaatst.

![](/content/images/mappenstructuur-abonneren-op-map.png)