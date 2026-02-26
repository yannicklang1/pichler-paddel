# Pichler Paddel – Website-Konzept

## 1. Farbschema & Design-Stil

### Farbpalette (60-30-10-Regel)

| Rolle | Farbe | Hex | Verwendung |
|-------|-------|-----|------------|
| **Primär (60%)** | Dunkles Waldgrün | `#1a3c2a` | Header, Footer, Hero-Hintergründe |
| **Sekundär (30%)** | Helles Limettengrün | `#4ade80` | Akzente, Hover-States, Icons, Badges |
| **Akzent (10%)** | Frisches Grün | `#22c55e` | CTA-Buttons, Highlights, Preisangaben |
| **Neutral Hell** | Grünliches Off-White | `#f6f9f7` | Seitenhintergrund |
| **Neutral Dunkel** | Dunkles Grün-Anthrazit | `#1a2e23` | Fließtext, Überschriften |
| **Zusatz** | Weiß | `#ffffff` | Karten, Container |

### Design-Stil

- **Modern-minimalistisch** mit sportlicher Energie
- Großzügiger Weißraum (Whitespace) für klare Lesbarkeit
- Abgerundete Karten (border-radius: 14–20px) mit dezenten Schatten
- Mobile-first responsive Design
- Schriften: **Syne** (Display/Headlines, 600–800), **Outfit** (Body, 300–700)
- Dezente Scroll-Animationen (fade-in-up mit IntersectionObserver)
- Sticky Header mit Glasmorphismus-Effekt beim Scrollen
- Diagonale Sektionsteiler für dynamische Wirkung

---

## 2. Website-Texte (Startseite)

### Hero-Sektion

- **H1:** Dein **Spiel.** Dein **Platz.** Jetzt **buchen.** *(Schlüsselwörter in Akzentfarbe hervorgehoben)*
- **H2:** Zwei Outdoor-Courts in Wien-Mauer – an der frischen Luft spielen, ohne weit zu fahren. Einfach online buchen und loslegen.
- **Hero-Hintergrund:** Outdoor-Padel-Foto + dunkler Grün-Gradient-Overlay
- **Badge:** 2 Outdoor-Courts in Mauer
- **Logo:** Minimalistisches SVG-Icon – stilisierter Padel-Schläger mit Perforationen und Ball
- **CTA primär:** Jetzt Platz buchen
- **CTA sekundär:** Preise & Zeiten ansehen

### Sektion: "In 3 Schritten auf dem Court"

| Schritt | Titel | Text |
|---------|-------|------|
| 01 | Datum wählen | Such dir deinen Wunschtermin aus – 7 Tage die Woche, von früh bis spät. |
| 02 | Slot buchen | Wähl zwischen 60 oder 90 Minuten und sichere dir deinen Court. |
| 03 | Spielen! | Komm vorbei, schnapp dir den Schläger und genieß dein Spiel an der frischen Luft! |

### Sektion: "Zwei Courts. Null Kompromisse."

Unsere beiden Outdoor-Padel-Plätze sind mit hochwertigem Kunstrasen, professioneller LED-Beleuchtung und erstklassigen Glaswänden ausgestattet – ruhig gelegen an der frischen Luft in Wien-Mauer.

**USP:** Kein weiter Weg in die Stadt – Top-Plätze Outdoor, ruhig gelegen, frische Luft.

**Features:**
- Profi-Kunstrasen (FIP-Standard)
- LED-Flutlicht für Abendspiele
- Umkleiden & Duschen vor Ort
- Schläger zum Mieten, Bälle vor Ort kaufbar

### Sektion: "Fair spielen, fair zahlen."

| Dauer | Off-Peak (Mo–Fr 08–16) | Prime Time (Mo–Fr ab 16, Sa/So/Feiertag) |
|-------|------------------------|------------------------------------------|
| 60 Minuten | 24 € | 32 € |
| 90 Minuten (Beliebt) | 33 € | 44 € |

Alle Preise pro Court (bis 4 Spieler). Schläger-Miete: 5 € pro Schläger. Bälle: 6 € pro Dose (3 Bälle).

### Kontakt-Sektion: "Komm vorbei – wir freuen uns auf dich!"

Du findest uns in Wien-Mauer (23. Bezirk, Liesing) – ruhig gelegen, mit Top-Courts an der frischen Luft. Fragen? Schreib uns einfach oder ruf kurz an.

---

## 3. FAQ-Sektion

### Frage 1: Wie buche ich einen Padel-Platz?
Ganz einfach: Wähle oben im Buchungstool dein Wunschdatum, die Uhrzeit und die Spieldauer (60 oder 90 Minuten). Nach der Online-Bezahlung erhältst du sofort eine Bestätigung per E-Mail. Das war's – einfacher geht's nicht.

### Frage 2: Kann ich meine Buchung stornieren oder umbuchen?
Klar! Bis 24 Stunden vor deinem gebuchten Slot kannst du kostenlos stornieren oder umbuchen. Nutze dafür einfach den Link in deiner Bestätigungs-E-Mail. Bei kurzfristigeren Absagen (unter 24 Stunden) wird der volle Betrag berechnet.

### Frage 3: Muss ich eigene Schläger mitbringen?
Nein, musst du nicht! Wir haben hochwertige Padel-Schläger zum Mieten vor Ort. Bälle kannst du bei uns direkt kaufen. Du brauchst nur Sportkleidung und saubere Sportschuhe – den Rest erledigen wir.

### Frage 4: Wie viele Spieler können auf einem Court spielen?
Padel wird klassisch im Doppel gespielt, also 4 Spieler pro Court. Du kannst aber auch zu zweit spielen – der Preis bleibt pro Court gleich, egal ob 2 oder 4 Spieler. Tipp: Teilt euch die Kosten und habt doppelt so viel Spaß!

---

## 4. Buchungs-Plugin-Empfehlungen (WordPress)

### 1. Court Reservation – Erste Wahl
- **Website:** https://wordpress.org/plugins/court-reservation
- **Preis:** Premium 129,99 $/Jahr | Ultimate 299,99 $/Jahr (mit WooCommerce-Zahlung)
- **Warum ideal:** Speziell für Padel/Tennis-Courts entwickelt, Kalenderansicht, unbegrenzte Plätze, DSGVO-konform, 5/5 Sterne
- **Empfehlung:** Ultimate-Plan (Online-Bezahlung via WooCommerce inkl. Stripe/PayPal)

### 2. Amelia
- **Website:** https://wpamelia.com
- **Preis:** Pro ab 149 $/Jahr
- **Warum ideal:** Zahlreiche Zahlungsmethoden (Stripe, PayPal, Mollie), SMS/WhatsApp-Benachrichtigungen, modernes UI, Google Calendar Sync
- **Setup:** Courts als "Ressourcen" konfigurieren

### 3. Simply Schedule Appointments
- **Website:** https://simplyscheduleappointments.com
- **Preis:** Professional 199 $/Jahr | Business 399 $/Jahr (Multi-Ressourcen)
- **Warum ideal:** 70.000+ Nutzer, 5-Minuten-Setup, Elementor/Divi-Integration, 30-Tage-Geld-zurück
- **Setup:** Business-Plan für Multi-Court-Buchung

### Vergleich

| Kriterium | Court Reservation | Amelia | Simply Schedule |
|-----------|------------------|--------|-----------------|
| Padel-spezifisch | Ja | Nein | Nein |
| Kosten (2 Courts + Zahlung) | ~300 $/Jahr | ~149 $/Jahr | ~399 $/Jahr |
| Zahlungsintegration | WooCommerce | Stripe, PayPal, Mollie | Stripe, PayPal |
| DSGVO-konform | Ja | Ja | Ja |

**Klare Empfehlung:** Court Reservation Ultimate

---

## 5. Seitenstruktur

```
/                → Startseite (One-Page: Hero, Schritte, Courts, Preise, FAQ, Kontakt)
/buchen          → Buchungsseite (Court Reservation Kalender)
/impressum       → Impressum
/datenschutz     → Datenschutzerklärung
/agb             → AGB / Buchungsbedingungen
```

## 6. Tech-Stack-Empfehlung

- **CMS:** WordPress
- **Theme:** Astra oder GeneratePress (leichtgewichtig, schnell)
- **Page Builder:** Elementor Pro oder Full-Site-Editing
- **Buchung:** Court Reservation Ultimate
- **Hosting:** Raidboxes oder All-Inkl.com (DACH-optimiert)
- **SSL:** Let's Encrypt
