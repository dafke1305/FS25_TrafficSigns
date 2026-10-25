# Traffic Signs — Handleiding

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

Voor het pakket **1.0.0.1** uit [deze release](https://github.com/dafke1305/FS25_TrafficSigns/releases/tag/v1.0.0.1). Deze instructies horen bij die ZIP, niet bij een andere build met hetzelfde versienummer.

## Installatie

1. Download **FS25_TrafficSigns.zip** onder Assets van de release. Behoud de bestandsnaam en pak de ZIP niet uit. De automatische GitHub Source code-archieven zijn niet de mod.
2. Plaats de ZIP in de ingestelde FS25-modsmap (op Windows gewoonlijk `Documents\My Games\FarmingSimulator2025\mods`) en schakel de mod in vóór het laden van de savegame. Deze scriptmods zijn voor PC/Mac.
3. Server en alle multiplayerclients moeten **dezelfde ZIP** hebben, niet alleen hetzelfde versienummer. Sluit het spel/stop de server en maak vóór bijwerken een saveback-up.

## Een bord plaatsen en bewerken

1. Open **Bouwen > Decoratie** en kies een richtingsbord. De release bevat twintig modellen, waaronder pijlen, kruispunt-/rotondeborden, afstandsborden en portalen boven de weg.
2. Draai en plaats het bord. De steunen moeten naast de weg en buiten actieve akkers staan. Een portaal mag de weg overspannen. Deze mod vereist voor plaatsing geen eigendom van de grond, maar controleert wel waar de steunen staan.
3. Stap uit en loop naar het bord. Bij een portaal of uitkragend bord zit het bewerkpunt naast de **rechtersteun**.
4. Gebruik **Bestemmingen bewerken / Edit destinations** in de contextuele F1-hulp. Kies een beschikbaar tekstveld, vul de bestemming, wegnaam, afrit of afstand in en bevestig met **Toepassen / Apply**.
5. Herhaal dit voor de andere velden. Een leeg veld verbergt de tekst. Maximaal **48 tekens per veld**; lange tekst wordt kleiner weergegeven.

Je moet bij de eigenaarboerderij horen of als in-game serverbeheerder zijn aangemeld, en dicht bij het bewerkpunt staan. Teksten worden met het bord opgeslagen en naar multiplayerclients gesynchroniseerd.

## Gedrag van de modellen

- Pijlvormige borden hebben alleen op de **voorkant** bewerkbare tekst. De metalen achterkant blijft leeg.
- Elk model biedt zijn eigen velden; een enkel paneel krijgt niet automatisch vier bestemmingen.
- Prijzen: 250 tot 7.000; dagelijks onderhoud: nul.
- Het zijn decoratieve wegwijzers. Ze wijzigen geen AI-verkeer of GPS-routes.

## Problemen oplossen

| Probleem | Controle |
| --- | --- |
| Geen bewerkactie | Stap uit, zoek het juiste bewerkpunt en controleer je boerderij of beheerdersrol. |
| Plaatsing op weg/akker geweigerd | Verplaats de fundering naar de berm of andere toegestane grond. Wacht wanneer grondgegevens nog laden. |
| Een geschilderde weg wordt niet herkend | Herkenning gebruikt de native weggegevens van de map; alleen een wegtextuur is onvoldoende. |
| Tekst ontbreekt | Controleer of het veld leeg is en of je naar de bedrukte kant kijkt. |

## Hulp vragen

Gebruik [het bug-/supportformulier van deze mod](https://github.com/dafke1305/FS25_TrafficSigns/issues/new/choose). Vermeld release/ZIP, FS25- en mapversie, singleplayer/host/client/dedicated, stappen, tijdstip en het volledige clientbestand `log.txt`; bij een dedicated-serverprobleem ook `server.log` van dezelfde sessie. Voeg relevante screenshots/video toe. De pakketcontrolecode staat in [PUBLICATION.json](PUBLICATION.json). Verwijder wachtwoorden, tokens en privéverbindingsgegevens vóór openbaar plaatsen. Gebruik voor privébewijs alleen een goedgekeurd privékanaal.

Standaardtoetsen zijn aanpasbaar. De actuele F1-hulp en je instellingen onder Besturing zijn leidend.
