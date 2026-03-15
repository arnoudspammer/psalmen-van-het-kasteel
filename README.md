# ☠️ Psalmen van het Kasteel - 16-bit Editie ☠️

Welkom bij **Psalmen van het Kasteel**! Een 16-bit middeleeuwse queeste gemaakt in pure HTML5, CSS en JavaScript (Canvas).

Gij zijt een ridder die een oud psalmenboek heeft gevonden in de ruïnes van Dracula's kasteel. Echter ontbreken er vele bladzijden. Het is aan jou om de verloren psalmrollen te vinden en je kennis van de Schrift te bewijzen. Beantwoord de vragen juist en ontvang goddelijke krachten om de demonen te verslaan.

## ✨ Features
*   **16-bit Pixel Art Stijl**: Volledig handgetekende sprites en animaties in code (geen externe afbeeldingsbestanden nodig).
*   **Vloeiende Rendering**: Geoptimaliseerde Canvas sprite-caching voor 60 FPS gameplay.
*   **Actie & Platforming**: Vecht tegen skeletten, vleermuizen en spoken met je zweep en subwapens.
*   **Educatief**: Leer en herken Bijbelse Psalmen om power-ups vrij te spelen.
*   **Aanpasbare Besturing**: Stel je eigen keyboard shortcuts in via het hoofdmenu.

---

## 🚀 Hoe speel je het spel op je computer?

Omdat het spel volledig in de browser draait, hoef je **geen software of servers te installeren**.

### Optie 1: Downloaden (Het makkelijkst)
1. Klik bovenaan deze GitHub-pagina op de groene knop **"<> Code"**.
2. Kies **"Download ZIP"**.
3. Pak het gedownloade `.zip` bestand ergens uit op je computer.
4. Dubbelklik op het bestand **`index.html`**. 
5. Het spel opent nu in je standaard webbrowser (Chrome, Edge, Firefox, Safari, etc.) en je kunt direct spelen!

### Optie 2: Via Git (Voor ontwikkelaars)
1. Open je terminal of command prompt.
2. Clone de repository:
   ```bash
   git clone https://github.com/arnoudspammer/psalmen-van-het-kasteel.git
   ```
3. Navigeer naar de map en open `index.html` in je browser.

---

## 🎮 Besturing (Standaard)

De besturing kan in het startscherm van het spel worden aangepast via **"⚙️ INSTELLINGEN"**. 

De standaard knoppen zijn:
*   **Pijltjestoetsen** - Lopen & Richten
*   **Z** - Springen
*   **X** - Aanvallen (Zweep)
*   **C** - Subwapen (Heilig Water) gebruiken (kost hartjes)
*   **I** - Inventaris (Psalmenboek) openen / sluiten

## 🛠️ Technische opbouw
Het project is onlangs opgesplitst voor betere leesbaarheid:
*   `index.html` - De structuur, menu's en het Canvas element.
*   `style.css` - Alle styling, layout en lettertypes.
*   `game.js` - De game engine, sprite definities, logica en rendering.

Veel speelplezier!
