# Kennisbank JenV Gegevens en Algoritmes
Deze repository bevat kaarten met relevante dingen (ontwikkelingen, projecten, tools, standaarden, etc.) in het kader van gegevensboekhouding.

Backup en synchronisatie tussen de verschillende gebruikers doen we via Github.

Alle informatie in de kennisbank is open en publiek in te zien.

## Kennisbank gebruiken
### Installatie
Download de Github Desktop (https://desktop.github.com/) of een andere git client en installeer deze.

Clone de kennisbank repository in Github Desktop: Add -> Clone Repository -> URL -> git@github.com:cdojenv/kennisbank.git en kies de directory waar deze moet komen te staan. (Selecteer indien gevraagd "For my own purposes").

Download Obsidian (https://obsidian.md/download) en installeer deze. Een commercial license hiervoor is 50 euro per jaar.

Open de kennisbank: File -> Open Vault -> Open folder as vault (Selecteer de directory van de hierboven geclonede repository.)

### Wijzigingen ophalen
Om de wijzigingen van anderen op te halen, kun je af en toe (bijvoorbeeld dagelijks) in de Github Client op "Fetch Origin" klikken om te kijken of er wijzigingen zijn, en "Pull Origin" indien dat zo is om ze binnen te halen.

### Bijdragen aan de kennisbank
#### Kaarten toevoegen
Als hoofdstructuur groeperen we de kaarten onder de JAGA teams:
- Algemeen
- Gegevensboekhouding
- Governance afsprakenstelsel
- Gegevensbeleid
- Metamodel
- Datagerelateerde wetten

Ieder team is verantwoordelijk voor het onderhouden van de eigen **kaarten** in het desbetreffende mapje onder kaarten. In dit mapje kun je nieuwe kaarten aanmaken. Daarbij leggen we beknopt vast: wat is het, waarom is het relevant, wat doen we ermee. Voor meer informatie verwijzen we naar de relevante bronnen. Een nieuwe kaart kan toegevoegd worden door te klikken op de eerste knop (new note) van knoppenbalk boven de kaarten folder structuur. Nadat een blanco kaart is aangemaakt, gebruik je de kaart template; deze is te vinden onder het vijfde knop (insert template) van de knoppenbalk aan linker bovenkant. Vervolgens kan er in het pop-up scherm gekozen worden voor de optie: kaart template.

#### Besluiten vastleggen
Daarnaast kunnen teams ook **besluiten** vastleggen in een eigen mapje onder besluiten. Hiervoor gebruiken we het [Markdown Any Decision Record format](https://kennisbank.gegevensboekhouding.nl/kaarten/Gegevensboekhouding/Markdown%20Any%20Decision%20Records%20(MADR)/). Gebruik ook hiervoor de beschikbare template.

#### Wijzigingen uploaden
Als je wijzigingen maakt in Obsidian, kun je in Github Desktop selecteren welke gewijzigde wijzigingen je lokaal wil vastleggen ("committen") door ze aan te vinken (of uit te vinken). Vervolgens geef je een titel en beschrijving voor de set aan wijzigingen en klik je op "Commit to main". Hierna kun je op "Push Origin" klikken om de wijzigingen naar Github (online) te uploaden, zodat anderen deze wijzigingen daar weer kunnen ophalen.

Wijzigingen die je wil terugdraaien in plaats van committen kan door met rechts te klikken en "Discard Changes" te klikken.
