---
title: Autodesk Docs - Status documenten
date: 2023-06-30T11:59:41.324Z
permalink: /autodesk-docs-status-documenten.html
eleventyNavigation:
  order: 0
  key: Autodesk Docs - Status documenten
  parent: Extern
---
De mappenstructuur van de Stad Gent is op het hoogste niveau gebaseerd op de ISO 19650 standaard:

![](/content/images/mappen-iso-19650.png)

![](/content/images/iso-19650-status.png)

Documenten worden aangemaakt in de bovenste mappen, en worden doorheen hun levenscyclus verplaatst of gekopieerd naar de onderste mappen.

* WIP = Work In Progress = interne keuken, deze documenten worden niet gedeeld met anderen
* Shared = deze documenten worden gedeeld met andere teams en met de opdrachtgever
* Shared owner = deze documenten worden **alleen** met de opdrachtgever gedeeld (bijvoorbeeld vertrouwelijke financiële informatie)
* Published = goedgekeurde documenten, geschikt voor een bepaalde fase van het project

![](/content/images/mappen-projectfases.png)

Voorbeeld:

1. Het architectenbureau maakt een Revit model, en bewaart dit in de map "01_WIP\02_ONT-ARB_Architectenbureau"

   * Dit document is enkel zichtbaar voor het architectenbureau
   * Er is geen naamgevingsstandaard van toepassing op dit moment
   * Bij iedere wijziging wordt het document telkens onder dezelfde naam bewaard.  Daardoor wordt er gebruik gemaakt van het versiebeheer binnen Autodesk Docs.

     * Het architectenbureau werkt verder aan dit document, tot en met een 5de versie (V5).
2. Het architectenbureau controleert het Revit model, en is van mening dat het geschikt is om te delen met het studiebureau technieken.\
   Het document wordt **gekopieerd** van de WIP map naar de Shared map: "02_Shared\02_ONT-ARB_Architectenbureau"

   * Gedeelde documenten moeten steeds in de map van de delende partij geplaatst worden.  Niet in die van de ontvanger.
   * Door een document te kopiëren, wordt enkel de op dat moment actuele versie gekopieerd.  Met andere woorden: ook al bevindt het document zich al op V5 in de WIP map, in de de shared map zal dit een V1 worden (=de eerste gedeelde versie).

     * Dit is perfect logisch.  De 4 voorgaande versies waren helemaal niet bedoeld om te delen.  Deze historiek mag niet mee gekopieerd worden.
   * De laatste positie in de naamgeving verwijst naar de projectfase en wordt ingevuld naargelang de fase waar men zich in bevindt.  Het gaat om het Revit model dat het volledige project zal doorlopen, waarop dus steeds verder gewerkt zal worden, maar telkens bij overgang naar een andere fase zal de aanduiding achteraan aangepast moeten worden.
3. Zodra de fase (bijvoorbeeld voorontwerp) ten einde loopt, en het Revit model werd gecontroleerd en goedgekeurd, zal het architectenbureau het opnieuw **kopieren**.  Deze keer naar de map "04_Published\04_VO_Voorontwerp"

   * De versie in de map “04_Published\04_VO_Voorontwerp” wordt dan V1.
     Dit is perfect logisch, deze versie werd immers goedgekeurd en zal niet meer gewijzigd worden na overgang naar de volgende fase.
   * Nu moet ook de naam van het document in de map “02_Shared\02_ONT-ARB_Architectenbureau” gewijzigd worden.
     De laatste positie in de naamgeving verwijst naar de projectfase, en moet dus correct ingevuld worden: nu dus DO i.p.v. VO.
     Zo kan men volgen welke fase lopende is voor dat specifieke document.

![](/content/images/naamgeving-fase-do.png)

Niet elk document moet alle statussen doorlopen (WIP => Shared => Published).  Sommige documenten kunnen meteen gedeeld of gepubliceerd worden.

Voorbeeld:

* BIM-extracten (DWG, PDF, ...) kunnen meteen in de Shared map bewaard worden 
* GRO documenten moeten niet gedeeld worden met andere projectpartners, en kunnen dus meteen in de Published map gepubliceerd worden.  Deze worden aangemaakt door de architect, en meteen gepubliceerd.