### Überblick
Dieses Projekt benutzt CSS und SCSS, um das Design der Website zu gestalten.
Der Stil wirkt modern, freundlich und übersichtlich. Hauptsächlich wurde mit warmen Farben, runden Ecken und klaren Abständen gearbeitet.

### Farben
Rot (#d62828) → Hauptfarbe für Navbar, Buttons, Footer
Gelb (#f7b801 / #ffcc00) → Akzentfarbe für Hero-Bereich und Logo
Dunkelgrau (#222) → Textfarbe
Weiß (#ffffff) → Karten, Formulare, Boxen
Beige Verlauf → Hintergrund der Seite

Ich habe versucht, dem Essen einen Fast-Food style zu geben.

### Layout & Aufbau

Am Anfang werden Standardabstände entfernt:
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

### Eigenschaften:
- Roter Hintergrund
- Gelbes Logo
- Weiße Links
- Flexbox für saubere Anordnung
- Hover-Effekt:

### Der obere Startbereich
- Gelben Hintergrund
- Große Überschrift
- Zentrierter Text

Dieser Bereich zieht direkt Aufmerksamkeit auf sich.

### Buttons
Buttons sind überall ähnlich gestaltet:

- Roter Hintergrund
- Weiße Schrift
- Runde Ecken
- Hover = dunkleres Rot

Das sorgt für ein einheitliches Design.

### Karten / Boxen

Zum Beispiel bei Menü-Produkten oder Angeboten:

Weißer Hintergrund
- Runde Ecken
- Schatten
- Abstand innen (Padding)


### Formulare

Inputs und Textareas haben:

- Gelbe Rahmen
- Runde Ecken
- Viel Platz innen

Dadurch sind Formulare angenehm zu benutzen.

### Responsive Design

Mit @media Queries wird die Seite an kleinere Geräte angepasst.

Beispiele:
- Menü wird kleiner
- Navbar untereinander
- Texte kleiner
- Hero Bereich niedriger

Sehr wichtig für Smartphones.

SCSS Vorteile im Projekt


Zusätzlich wurde SCSS genutzt.

- Variablen:
- $main-red
- $main-yellow
- $radius
- $shadow


### Das Projekt wirkt:

- modern
- freundlich
- übersichtlich
- warm
- passend für Food / Restaurant
