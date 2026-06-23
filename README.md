# 🐂 Carte interactive des courses camarguaises 2026

Visualisation géographique du calendrier officiel de la [Fédération Française de la Course Camarguaise (FFCC)](https://www.ffcc.info), absente du site officiel.

👉 **[Voir la carte en ligne](https://thomaspgc.github.io/carte-course-camarguaise)**

---

## Sommaire

- [Français](#français)
- [Occitan](#occitan)
- [Interlingua](#interlingua)
- [English](#english)

---

<a name="français"></a>
## 🇫🇷 Français

### Fonctionnalités

- 📍 Toutes les courses de la saison 2026 placées sur une carte OpenStreetMap
- 🥇 Marqueurs colorés par niveau : or (Trophée As), argent (Trophée Avenir), bleu (autres)
- 🕐 Détail par commune : date, heure, niveau, tarif
- 📅 Filtre par période pour trouver les courses proches dans le temps

### Stack technique

| Outil | Rôle | Licence |
|---|---|---|
| [Playwright](https://playwright.dev) (Microsoft) | Scraping du calendrier FFCC | Apache 2.0 |
| [Nominatim](https://nominatim.org) (OpenStreetMap) | Géocodage des communes | ODbL |
| [Leaflet.js](https://leafletjs.com) (V. Agafonkin) | Carte interactive | BSD 2-Clause |
| [OpenStreetMap](https://openstreetmap.org) | Fond de carte | ODbL |
| [GitHub Pages](https://pages.github.com) | Hébergement statique | - |

### Structure du projet

```
├── index.html        # Carte interactive (Leaflet)
├── scraper.py        # Scraping du calendrier FFCC
├── geocoder.py       # Géocodage des communes
├── courses.json      # Données brutes scrappées
├── courses_geo.json  # Données enrichies avec coordonnées GPS
├── README.md         # Ce fichier
└── LICENSE           # Licence CC BY-SA 4.0
```

### La course camarguaise

La course camarguaise, ou course libre, est une discipline sportive et culturelle traditionnelle du sud de la France, pratiquée principalement dans le Gard, l'Hérault, les Bouches-du-Rhône et le Vaucluse.

Le principe : des raseteurs cherchent à enlever à l'aide d'un crochet (le raset) des attributs (une cocarde, deux glands et deux ficelles) attachés aux cornes du taureau. Les courses se déroulent dans des arènes villageoises, souvent lors des fêtes votives, de juin à octobre, avec des événements de prestige dans les arènes romaines de Nîmes et d'Arles.

Le taureau est au cœur de la discipline : il acquiert au fil de sa carrière une véritable notoriété. Les individus les plus vifs à répondre aux sollicitations des raseteurs tout en défendant gaillardement leurs attributs sont suivis avec passion par les fanas de bouvine. Certains deviennent de véritables vedettes, acclamées à chaque entrée en piste.

La FFCC (Fédération française de course camarguaise) organise plusieurs niveaux de compétition, avec entre autres le Trophée avenir (jeunes en début de carrière) et le Trophée des as (l'élite de la discipline).

### Licence

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) © 2026 ThomasPGC

Pour tout usage commercial, merci de prendre contact.

### Contact

📧 thomaspgc@proton.me

Mes sites pro :
- [insta-note.com](https://insta-note.com)
- [leptotech — Crealead](https://www.crealead.com/nos-entrepreneurs/leptotech#services)

### Contribuer

Les corrections de géocodage, ajouts de communes manquantes ou améliorations de l'interface sont les bienvenus via pull request.

---

<a name="occitan"></a>
## 🌞 Óucitan

### Fouciounnalità

- 📍 Touti lei courso de la sason 2026 sus uno carto OpenStreetMap
- 🥇 Marcadour couloura per nivèu : or (Trofèu dei As), argent (Trofèu Aveni), blàu (autrei)
- 🕐 Detalh per comuno : dato, uro, nivèu, tarife
- 📅 Filtre per periòde pèr trouba lei courso procho dins lou tèms

### La courso camargueso

La courso camargueso, o courso liéuro, es uno disciplino esportivo e culturaio tradiciounalo dóu Miejour de Franço, practicado principaumen dins lou Gard, l'Éraur, lei Bóuco-dóu-Ròse e lou Vaucluso.

Lou principi : de rasataire cercon à óustar emé un crouchet (lou raset) d'atribut (uno cocardo, dous gland e dous ficèlo) atacat i banno dóu biòu. Lei courso se fan dins d'areno de village, souvènt pèr lei fésto votivo, de junh à óutobre, emé d'evenimen de prestigi dins lei areno romano de Nimes e d'Arle.

Lou biòu es au còr de la disciplino : adqier au long de sa carriero uno veritablo notorietà. Li plus viu à respondre i soulicitacioun dei rasataire tout en defendènt galhardamen si atribut soun segui emé passien pèi li fano de bouvino. Certan devènon de veritablo vedeto, aclamado à chasco intrado en pisto.

La FFCC (Federacioun Franceso de Courso Camargueso) óurganifo plusiour nivèu de competicioun, emé entre autre lou Trofèu Aveni (jouine en debuto de carriero) e lou Trofèu dei As (l'elito de la disciplino).

### Licènci

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) © 2026 ThomasPGC

Pèr tout usatge comerciau, mercé de prendre countacte.

### Countacte

📧 thomaspgc@proton.me

Miéi site proufessiounau :
- [insta-note.com](https://insta-note.com)
- [leptotech — Crealead](https://www.crealead.com/nos-entrepreneurs/leptotech#services)

### Countribuï

Lei correccioun de geocodage, ajust de comunas mancanto o amelhouracioun de l'interfàci soun li benvengudo vio pull request.

---

<a name="interlingua"></a>
## 🌍 Interlingua

### Functionalitates

- 📍 Tote le cursas del saison 2026 sur un carta OpenStreetMap
- 🥇 Marcatores colorite per nivel : auro (Tropheo As), argento (Tropheo Avenir), blau (alteres)
- 🕐 Detalio per communa : data, hora, nivel, tarifa
- 📅 Filtro per periodo pro trovar le cursas proxime in le tempore

### Le cursa camarguese

Le cursa camarguese, o cursa libere, es un disciplina sportive e cultural traditional del sud de Francia, practicate principalemente in le Gard, le Hérault, le Bouches-du-Rhône e le Vaucluse.

Le principio : rasatores cerca a remover con un croc (le raset) attributos (un cocarda, duo glandas e duo filamentos) attachate al cornos del tauro. Le cursas se desenrola in arenas de villagio, sovente durante le festas votive, de junio a octobre, con eventos de prestigio in le arenas romane de Nîmes e de Arles.

Le tauro es al corde del disciplina : ille acquiri durante su carriera un veritable notorietate. Le individuos le plus vive a responder al sollicitationes del rasatores, defendendose galliardemente su attributos, es sequite con passion per le fanas de bouvina. Alicunes deveni veritabile vedetas, acclamate a cata entrata in pista.

Le FFCC (Federation Francese de Cursa Camarguese) organisa plure niveles de competion, includente le Tropheo Avenir (juvenes in initio de carriera) e le Tropheo del As (le elite del disciplina).

### Licentia

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) © 2026 Thomas PGC

Pro tote uso commercial, gratias de contactar nos.

### Contacto

📧 thomaspgc@proton.me

Mi sitos professional :
- [insta-note.com](https://insta-note.com)
- [leptotech — Crealead](https://www.crealead.com/nos-entrepreneurs/leptotech#services)

### Contribuer

Le correctiones de geocodage, additiones de communas mancante o meliorationes del interfacie es benvenite via pull request.

---

<a name="english"></a>
## 🇬🇧 English

### Features

- 📍 All races of the 2026 season displayed on an OpenStreetMap
- 🥇 Color-coded markers by level : gold (Trophée As), silver (Trophée Avenir), blue (others)
- 🕐 Details per town : date, time, level, admission price
- 📅 Date range filter to find nearby races in time

### Technical stack

| Tool | Role | Licence |
|---|---|---|
| [Playwright](https://playwright.dev) (Microsoft) | Scraping the FFCC calendar | Apache 2.0 |
| [Nominatim](https://nominatim.org) (OpenStreetMap) | Geocoding of towns | ODbL |
| [Leaflet.js](https://leafletjs.com) (V. Agafonkin) | Interactive map | BSD 2-Clause |
| [OpenStreetMap](https://openstreetmap.org) | Map tiles | ODbL |
| [GitHub Pages](https://pages.github.com) | Static hosting | - |

### Project structure

```
├── index.html        # Interactive map (Leaflet)
├── scraper.py        # FFCC calendar scraper
├── geocoder.py       # Town geocoding
├── courses.json      # Raw scraped data
├── courses_geo.json  # Data enriched with GPS coordinates
├── README.md         # This file
└── LICENSE           # CC BY-SA 4.0 licence
```

### The course camarguaise

The course camarguaise, or course libre, is a traditional sporting and cultural discipline from the south of France, practised mainly in the Gard, Hérault, Bouches-du-Rhône and Vaucluse departments.

The principle : raseteurs attempt to remove with a hook (the raset) a set of attributes (a cockade, two tassels and two ribbons) attached to the bull's horns. Races take place in village arenas, often during local festivals, from June to October, with prestigious events held in the Roman arenas of Nîmes and Arles.

The bull is at the heart of the discipline : over the course of his career he builds a genuine reputation. The most agile individuals — those who respond sharply to the raseteurs while boldly defending their attributes — are followed with passion by bouvine enthusiasts. Some become true stars, greeted with acclaim at every entry into the arena.

The FFCC (Fédération Française de Course Camarguaise) organises several levels of competition, including the Trophée Avenir (young at the start of their career) and the Trophée des As (the elite of the discipline).

### Licence

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) © 2026 ThomasPGC

For any commercial use, please get in touch.

### Contact

📧 thomaspgc@proton.me

My professional websites :
- [insta-note.com](https://insta-note.com)
- [leptotech — Crealead](https://www.crealead.com/nos-entrepreneurs/leptotech#services)

### Contributing

Geocoding corrections, missing towns or interface improvements are welcome via pull request.
