# 🚗 ANWB Planner Tool
![mcbookAnwb](https://github.com/Daan645/proof-of-concept/assets/54812898/1c800fb9-3165-4d2c-9c8d-4cccba917fbc)

## 🔗 Link naar website
<a href="https://proof-of-concept-eqsl.onrender.com/" alt="ANWB Weekplanner Website">Bekijk hier de website</a>

## 📄 Inhoudsopgave
* [✏️ Beschrijving](#-beschrijving)
* [💻 Gebruik](#-gebruik)
* [🔎 Ontwerp](#-ontwerp)
* [🎮 Features](#-features)
* [✅ Waar ben ik trots op?](#-waar-ben-ik-trots-op)
* [❌ Waar liep ik tegen aan en hoe heb ik het opgelost?](#-waar-liep-ik-tegen-aan-en-hoe-heb-ik-het-opgelost)
* [🎯 Wat wil ik nog maken?](#-wat-wil-ik-nog-maken)
* [📡 Tech stack](#-tech-stack)
* [🧰 Tools](#-tools)
* [🔧 Installatie](#-installatie)
* [🔓 Licentie](#-licentie)

## ✏️ Beschrijving
Planner voor de ANWB waarop zij op weekbasis de piket diensten in moeten plannen en kunnen bekijken.

## 💻 Gebruik
<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->
### User story
Als medewerker van de ANWB wil ik kunnen zien wie er per week werkt en als welke functie diegene staat. Om dit op te lossen heb ik een week planner gemaakt.
### Gebruik van de week planner
Door op selecteer week te klikken krijg je een keuze menu waar je de gewenste week kunt kiezen waarin jij wilt zien wanneer iedereen werkt:

![ANWB-Demo](https://github.com/Daan645/proof-of-concept/assets/54812898/78ac4d4d-ed8e-4420-869d-9344525a4d18)

## 🔎 Ontwerp
Bij het ontwerp is volledig gebruikt gemaakt van het kleuren pallet uit de ANWB style guide zodat dit aansluit bij de huisstijl van de ANWB. Alle kleuren zijn toegevoegd in een :root en zijn dus makkelijk aantepassen indien nodig.

## 🎮 Features

### Responsive page
Doormiddel van media queries is de pagina responsive en te gebruiken op elk scherm formaat!

### Volledig toegankelijk menu
Het menu is volledig met html css gemaakt waardoor deze ook werkend is op apparaten zonder javascript. Ik heb hierbij gebruik gemaakt van een input.

### Image optimalisatie (layout shifting)
Ik heb de images een standaard width en height gegeven zodat dit layout shifting voorkomt.

### API optimalisatie
Ik haal alleen de benodigde velden uit de API waardoor de website sneller is.

### Dropdown week keuze menu
Ik heb een dropdown gemaakt waarin je alle weeknummers kunt selecteren, deze weeknummers worden allemaal uit de API opgehaald en is dus geheel dynamisch

### Week planning bekijken
Door middel van prevent default kun je de weekplanning op dezelfde pagina bekijken zonder deze te hoeven herladen. Alle namen, rollen, weken en assesments zijn uit de API opgehaald en worden dus automatisch bijgewerkt wanneer deze dat ook in de API zijn.

## ✅ Waar ben ik trots op?
### Toegankelijk hamburger menu
Ik heb een hamburger menu gemaakt zonder js te gebruiken dit heb ik voorelkaar gekregen met een verborgen input. Door het op deze manier te doen werkt het menu nogsteeds met zonder js.

### Server peformance / alle medewerkers ophalen, tegelijkertijd de weken en de diensten ophalen
Dit was erg ingewikkeld aangezien ik weinig ervaring had met directus en ik met koppel tabellen moest werken. Na veel stoeien is het mij gelukt om zo te filteren dat ik alleen de data heb die ik nodig heb zodat de website lekker vlot blijft!

## ❌ Waar liep ik tegen aan en hoe heb ik het opgelost?
### Alle medewerkers ophalen, tegelijkertijd de weken en de diensten ophalen
Ik liep hier erg tegen aan omdat directus vrij nieuw voor mij was. Wel begreep ik de logica al een beetje omdat ik eerder met MYSQL heb gewerkt. Om dit optelossen heb ik hulp gevraagd bij een docent die liet mij zien dat directus een filter functie heeft. Na te testen en experimenteren welke json data ik terug kreeg was het mij uiteindelijk gelukt.

### Server peformance
Tijdens het ophalen van alle data die ik nodig had merkte ik dat ik bijna alle gegevens in de hele database meenam. Ik heb toen verder geëxperimenteerd om zo uiteindelijk alleen de data op te halen die ik daadwerkelijk nodig had.

## 🎯 Wat wil ik nog maken?
- Dashboard om mensen in te plannen
- Vakantie planner
- Kalender view op home
- Ruilen van dienst
  
## 📡 Tech stack
- HTML
- CSS
- JS
- EJS
- Express
- Directus

## 🧰 Tools
- PHP storm
- Render

## 🔧 Installatie
1. Clone deze repository
2. Open de repository met een code editor naar keuze
3. Open het terminal in de code editor
4. Typ **npm install** in om alle benodigdheden voor het project te installeren
5. Gebruik de link <a href="http://localhost:8001/">http://localhost:8001/</a> om het project lokaal te bekijken
6. Mocht je het project online bekijken dan kan dat via <a href="https://proof-of-concept-eqsl.onrender.com/" alt="ANWB Weekplanner Website">deze link.</a>

## 🔓 Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
