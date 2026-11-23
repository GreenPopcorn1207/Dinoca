# 🦕🌊 Dinoca – 100 Level Türkisch mit Dinos, Urmenschen & Unterwasserwelt

**Dinoca** ist eine interaktive, browserbasierte Sprachlern-App zum spielerischen Lernen von **Türkisch** – verpackt als Sammel- und Schlüpfspiel mit **100 animierten Wesen**, **12 Biomen** und **zwei interaktiven Weltkarten**.

Die komplette App läuft als **einzelne HTML-Datei** ohne externe Bibliotheken, Frameworks oder Server – einfach herunterladen, im Browser öffnen oder direkt über GitHub Pages hosten.

---

## ✨ Highlights & Features

* **100 Level in 2 Welten & 12 Biomen:** 800 türkisch-deutsche Vokabelpaare (8 pro Level) und 200 Satzbau-Übungen (2 pro Level) – von ersten Begrüßungen (*Merhaba*, *Günaydın*) über *Kahvaltı*, *Lokanta* und *Geçmiş Zaman* bis hin zu YOLO, frechen Sprüchen, typischen Ausrufen und türkischen Redewendungen.
* **100 animierte Sammelwesen (Inline-SVG):** Alle Kreaturen blinzeln, atmen, wackeln mit Schwanz oder Flossen und reagieren beim Antippen mit Hüpf-Animationen, Herz-/Blasen-Effekten und türkischen Sprüchen:
  * 🦕 **41 Dinosaurier & Urzeittiere** (u. a. *Rexiko*, *Üçboynuz*, *Şimşek*)
  * 🦴 **9 Menschenaffen & Urmenschen** (u. a. *Proko*, *Lucy*, *Sapi*)
  * 🦈 **15 Haiarten** (u. a. *Köpekbalığı*, *Çekiç*, *Meggy*)
  * 🐋 **18 Orcas, Wale & Delfine** (u. a. *Orkiko*, *Mavidev*, *Tekboynuz*)
  * 🦭 **17 Seehunde, Seerobben, Seelöwen & Walross** (u. a. *Fokçuk*, *Akdeniz*, *Fildişi*)
* **Abwechslungsreiche Quiz-Formate:**
  * Vokabel-Spickzettel mit Vorlesefunktion vor jedem Level
  * Multiple Choice (🇹🇷 Türkisch → Deutsch & 🇩🇪 Deutsch → Türkisch)
  * 🎧 Hörverstehen (normales & langsames Sprechtempo)
  * 🔗 Zuordnungspaare (4 Paare verbinden)
  * 🧩 Satzbau mit antippenbaren Wort-Kacheln
* **14 Ei-Typen & Schlüpf-Animation:** Mit jeder richtigen Antwort bekommt das Ei neue Risse, wackelt und schlüpft am Ende des Levels mit Fanfare und Konfetti-Regen.
* **Zwei interaktive Weltkarten:** Urzeit-Weltkarte (Level 1–50) und Unterwasser-Weltkarte (Level 51–100) mit Biom-Zoom, Eier-Anzeige, Spotlight-Steckbrief und Gruppen-Gruß.
* **Großes 100-Arten-Lexikon:** Filterbar nach Kategorie (Haie, Orcas & Wale, Seehunde & Robben, Dinos, Urmenschen, Gesammelte) inkl. Steckbrief, Erdzeitalter/Lebensraum und vorlesbarem Spruch.
* **Türkische Sprachausgabe (`tr-TR`) & 🐢 Langsam-Modus:** Nutzt die eingebaute Web Speech API des Browsers für Vokabeln, Hörverstehen und Kreaturensprüche.
* **Web-Audio-Soundeffekte & lokaler Spielstand:** Fortschritt, Sterne und Einstellungen werden automatisch im `localStorage` unter `dinoca_tr_100_save_v1` gespeichert (unabhängig von anderen Sprachversionen).

---

## 🗺️ Die 2 Welten & 12 Biome

### 🦕 Urzeit-Welt (Level 1–50)

| Biom | Level | Themen |
| :--- | :---: | :--- |
| 🌋 **Vulkan-Tal** | 1–8 | Begrüßungen, Zahlen 1–100, Vorstellen, Farben, Familie, Körper, Gefühle |
| 🌿 **Urwald-Dschungel** | 9–16 | Natur, Obst & Gemüse, *Kahvaltı* & Café, *Lokanta*, *Dondurma*, Tiere, Zuhause & Möbel |
| 🌊 **Kristall-Lagune** | 17–23 | Meer & Strand, Wetter, Jahreszeiten, Wochentage, Uhrzeit, Hobbys & Sport |
| ☁️ **Wolken-Gipfel** | 24–29 | Verkehr, Wegbeschreibung, Stadt, Bahnhof & Flughafen, Hotel & Urlaub, Geografie |
| 🏜️ **Bernstein-Wüste** | 30–36 | Kleidung, Einkaufen & Basar, Verben I & II, Schule, Berufe, Technik & Alltag |
| ❄️ **Polar- & Sternengipfel** | 37–41 | Adjektive & Gegenteile, Gesundheit, Kochen & Rezepte, Feste & Feiern, Märchen |
| 🦴 **Tal der Evolution** | 42–50 | Vergangenheit (*Geçmiş Zaman*), Zukunft, Meinungen, Freundschaft, Kultur, Umwelt & Finale |

### 🌊 Unterwasserwelt (Level 51–100)

| Biom | Level | Themen |
| :--- | :---: | :--- |
| 🪸 **Korallenriff & Haibucht** | 51–60 | YOLO, freche Sprüche, Korallenriff, Snacks, Chill, Action, Style, Komplimente, Strandparty |
| 🌌 **Geheimnisvolle Tiefsee** | 61–65 | Charakter, türkische Drama-Ausrufe (*Aman Allah'ım!*), Weisheit, Tiefsee-Magie, Rekorde |
| 🐋 **Wal- & Orca-Reich** | 66–77 | Türkische Redewendungen, Teamwork, Musik, Nachdenken, Humor, Fantasie, Reisen, Charme |
| 🦭 **Sonnen-Lagune & Robbenfelsen** | 78–89 | Abenteuer, Ziele, Stürme, Tropen, Spielen, Kreativität, Kosenamen, *Merhaba Türkiye!* |
| 🧊 **Eis- & Seelöwenküste** | 90–100 | Gute Vibes, Mode, Ausreden & Ironie, Krimis, Essen mit Freunden, Mut, Level-100-Finale |

---

## 🚀 Start & Nutzung

### Lokal im Browser
1. Datei `dinoca_index.html` herunterladen (bei Bedarf in `index.html` umbenennen).
2. Per Doppelklick in einem modernen Browser (Chrome, Edge, Safari, Firefox) öffnen.
3. Direkt mit **Level 1** (Urzeit-Welt) oder **Level 51** (Unterwasserwelt) loslegen – beide Welten sind von Anfang an zugänglich!

### Hosting über GitHub Pages
1. Repository erstellen und die Datei als `index.html` ins Hauptverzeichnis hochladen.
2. In den Repository-Einstellungen unter **Settings → Pages** den Branch (z. B. `main` / `/ (root)`) aktivieren.
3. Kurz warten und die fertige GitHub-Pages-URL im Browser oder auf dem Smartphone öffnen.

---

## ⚙️ Einstellungen in der App

Über das Zahnrad-Symbol (`⚙️`) in der oberen Leiste lassen sich folgende Optionen umschalten:

* **🔊 Soundeffekte:** Ein-/Ausschalten der Web-Audio-Töne und Schlüpf-Fanfare.
* **🗣️ Sprachausgabe (Türkisch):** Aktiviert/Deaktiviert die `tr-TR`-Sprachausgabe.
* **🐢 Langsamer Modus:** Reduziert das Sprechtempo für besseres Verstehen.
* **🧪 Test-Modus:** Schaltet sofort alle 100 Level in beliebiger Reihenfolge frei.
* **✨ Alle 100 Wesen Vorschau:** Zeigt sämtliche 100 animierten Wesen sofort auf beiden Weltkarten und im Lexikon.
* **🗑️ Fortschritt löschen:** Setzt alle Sterne und geschlüpften Wesen zurück.

---

## 🛠️ Verwendete Technologien

* **HTML5, CSS3 & Vanilla JavaScript** (Single-File-Architektur, 0 externe Abhängigkeiten)
* **Inline-SVG & CSS-Keyframes** für alle 100 animierten Kreaturen, 14 Eier und beide Weltkarten
* **Web Speech API (`speechSynthesis`)** für türkische Aussprache (`tr-TR`)
* **Web Audio API** für synthetisierte Soundeffekte
* **HTML5 Canvas** für Konfetti-Animationen
* **`localStorage`** für die lokale Spielstandsspeicherung

> **Hinweis zur Sprachausgabe:** Für die beste Aussprache sollte im Betriebssystem oder Browser eine türkische Stimme (`tr-TR`) verfügbar sein. In Chrome, Edge und Safari (iOS/macOS) ist diese in der Regel direkt nutzbar.
