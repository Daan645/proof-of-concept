> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# ANWB Planner Tool
![mcbookAnwb](https://github.com/Daan645/proof-of-concept/assets/54812898/1c800fb9-3165-4d2c-9c8d-4cccba917fbc)

## Inhoudsopgave
  * [✏️ Beschrijving](#beschrijving)
  * [💻 Gebruik](#gebruik)
  * [🔎 Kenmerken](#kenmerken)
  * [🔧 Installatie](#installatie)
  * [🗝️ Licentie](#licentie)

## ✏️ Beschrijving
Maak voor de ANWB een planner tool, waarmee er per week piket diensten geplant en bekeken kunnen worden. Zowel de naam als functie moet zichtbaar zijn in de week planning. 
<!-- Voeg een mooie poster visual toe 📸 -->
<a href="https://proof-of-concept-eqsl.onrender.com/" alt="ANWB Weekplanner Website">Bekijk hier de website</a>

## 💻 Gebruik
<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->
### User story
Als medewerker van de ANWB wil ik kunnen zien wie er per week werkt en als welke functie diegene staat. Om dit op te lossen heb ik een week planner gemaakt.
### Gebruik van de week planner
Door op selecteer week te klikken krijg je een keuze menu waar je de gewenste week kunt kiezen waarin jij wilt zien wanneer iedereen werkt:

![ANWB-Demo](https://github.com/Daan645/proof-of-concept/assets/54812898/78ac4d4d-ed8e-4420-869d-9344525a4d18)

## 🔎 Kenmerken

### Ontwerp
Bij het ontwerp is volledig gebruikt gemaakt van het kleuren pallet uit de ANWB style guide zodat dit aansluit bij de huisstijl van de ANWB. Alle kleuren zijn toegevoegd in een :root en zijn dus makkelijk aantepassen indien nodig.

### Features

#### Responsive page
Doormiddel van media queries is de pagina responsive en te gebruiken op elk scherm formaat!

#### Volledig toegankelijk menu
Het menu is volledig met html css gemaakt waardoor deze ook werkend is op apparaten zonder javascript. Ik heb hierbij gebruik gemaakt van een input.

#### Image optimalisatie (layout shifting)
Ik heb de images een standaard width en height gegeven zodat dit layout shifting voorkomt.

#### API optimalisatie
Ik haal alleen de benodigde velden uit de API waardoor de website sneller is.

#### Dropdown week keuze menu
Ik heb een dropdown gemaakt waarin je alle weeknummers kunt selecteren, deze weeknummers worden allemaal uit de API opgehaald en is dus geheel dynamisch

#### Week planning bekijken
Door middel van prevent default kun je de weekplanning op dezelfde pagina bekijken zonder deze te hoeven herladen. Alle namen, rollen, weken en assesments zijn uit de API opgehaald en worden dus automatisch bijgewerkt wanneer deze dat ook in de API zijn.

### Technieken
- HTML
- CSS
- JS
- EJS
- Express

### Tools
- PHP storm
- Render

## 🔧 Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->
1. Clone deze repository
2. Open de repository met een code editor naar keuze
3. Open het terminal in de code editor
4. Typ **npm install** in om alle benodigdheden voor het project te installeren
5. Gebruik de link <a href="http://localhost:8001/">http://localhost:8001/</a> om het project lokaal te bekijken
6. Mocht je het project online bekijken dan kan dat via <a href="https://proof-of-concept-eqsl.onrender.com/" alt="ANWB Weekplanner Website">deze link.</a>

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
