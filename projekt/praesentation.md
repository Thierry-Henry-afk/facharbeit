---
marp: true
---

![bg cover](bilder/Hintergrundbild.praesentation.png)

# Passwortmanager
### Henry Wolf, 10d

---

<style>
section.title-slide h1 {
  position: absolute;
  top: 38%;
  left: 80px;
  width: calc(100% - 160px);
  text-align: left;
  margin: 0;
}

section.title-slide h3 {
  position: absolute;
  top: 53%;
  left: 80px;
  width: calc(100% - 160px);
  text-align: left;
  margin: 0;
}

section.content-slide h1 {
  position: absolute;
  top: 25px;
  left: 40px;
  right: 40px;
  text-align: left;
  margin: 0;
}

section.content-slide h2,
section.content-slide h3 {
  position: static;
  text-align: left;
  margin: 25px 40px 12px;
}

section.content-slide ul {
  position: static;
  margin: 100px 40px 0;
  padding-left: 25px;
}

section.content-slide p {
  position: static;
  margin: 12px 40px;
}

section.content-slide table {
  font-size: 92%;
}

section.content-slide th,
section.content-slide td {
  padding: 3px;
}

section.platform-slide h1 {
  position: absolute;
  top: 25px;
  left: 40px;
  right: 40px;
  text-align: left;
  margin: 0;
}

section.platform-slide h2,
section.platform-slide h3 {
  position: static;
  text-align: left;
  margin: 15px 40px 8px;
}

section.platform-slide ol,
section.platform-slide ul {
  position: static;
  margin: 8px 35px;
  padding-left: 28px;
  font-size: 30px;
  line-height: 1.2;
}

section.platform-slide li {
  margin-bottom: 6px;
}

section.platform-slide li p,
section.platform-slide p {
  position: static;
  margin: 5px 0;
  line-height: 1.2;
}

section.usability-slide h1 {
  position: absolute;
  top: 25px;
  left: 40px;
  right: 40px;
  text-align: left;
  margin: 0;
}

section.usability-slide h1 {
  position: absolute;
  top: 25px;
  left: 40px;
  right: 40px;
  text-align: left;
  margin: 0;
}

section.usability-slide .usability-layout {
  display: grid;
  grid-template-columns: 0.6fr 1.8fr;
  gap: 15px;
  align-items: center;
  margin: 65px 25px 10px;
}

section.usability-slide .usability-image {
  grid-column: 1 / -1;
  width: 100%;
  text-align: center;
}

section.usability-slide .usability-image img {
  width: 100%;
  height: auto;
  max-height: 500px;
  object-fit: contain;
  border-radius: 8px;
}

</style>



# Was ist ein Passwortmanager?
- Cybersicherheitstool
- Speichert und füllt Passwörter automatisch aus
- Generiert sichere Passwörter
- Man muss sich nur ein Masterpasswort merken
## Meine Leitfrage:
**Macht ein Passwortmanager meine Passwörter sicherer, oder entstehen dadurch neue Risiken?**
_Warum habe ich diese Leitfrage gewählt?_

---
<!-- _class: content-slide -->
# Proton Pass & NordPass & Bitwarden

|| NordPass | Bitwarden | Proton Pass |
|----------|----------|----------|----------|
| Nutzer weltweit  | über 11 Millionen Nutzer & über 11.500 Unternehmen  | 15 Millionen Benutzer & über 80.000 Unternehmen   | Über 100 Millionen Menschen und Unternehmen  |
| Verschlüsselung  | nutzt die XChaCha20-Verschlüsselung   |  verwendet AES-CBC 256-Bit-Verschlüsselung für Ihre Tresor-Daten   | 256-Bit-AES-GCM-Tresorverschlüsselung   |
| Kostenlos für Privatpersonen? | Kostenloses Paket für Privatpersonen  | Gratis Account für Privatpersonen   |  Kostenloses Paket für Privatpersonen |
| Sitz | Genaue Anschrift nicht gefunden| Santa Barbara, Kalifornien, USA | Genf (Plan-les-Ouates), Schweiz  |


---

<!-- _class: criteria-slide -->

# Meine Kriterien

1. Sicherheit
   - **Frage:** *Wie sicher schützt der Passwortmanager meine gespeicherten Passwörter?*
2. Benutzerfreundlichkeit
   - **Frage:** *Wie einfach lässt sich der Passwortmanager bedienen?*
3. Kosten
   - **Frage:** *Wie viel kostet der Passwortmanager und welche Funktionen bekomme ich dafür?*

---
<!-- _class: platform-slide -->
# Proton Pass
1. Entwickler:
   - Schweizer Unternehmen Proton AG
2. Markteinführung:
    - Sommer 2023
3. Sicherheitsarchitektur:
    - Ende-zu-Ende-Verschlüsselung (E2EE)
4. Plattformen: 
    - Windows, macOS, Linux, IOS, Android und Browser-Erweiterungen für Firefox, Chrome, Brave und Edge
5. Serverstandorte:
    - Schweiz
    - Deutschland
    - Norwegen
  
---
# Sicherheit
 - Ende-zu-Ende-Verschlüsselung (E2EE)
 - Zero-Knowledge-Prinzip
 - Serverstandorte
 - E-Mail-Aliase
 - Secure Remote Password (SRP)-Protokoll
 - Tresorverschlüsselung
 - Elementverschlüsselung
 - Key Transparency

---
<!-- _class: usability-slide -->

# Benutzerfreundlichkeit
- **Proton Pass Desktop-App ist in drei Bereiche unterteilt.**
  
  
<div class="usability-layout">
  <div></div>

  <div class="usability-image">

  ![Proton Pass Oberfläche](bilder/proton_pass_desktop_app.webp)

  </div>
</div>
  

---
# Kosten 
| Kategorie | Preis | Wichtigste Funktionen |
|---|---:|---|
| **Proton Free** | 0 €/Monat | Unbegrenzte Logins und Geräte, Passwortgenerator, 10 E-Mail-Aliasse, Passkey-Unterstützung |
| **Pass Plus** | 4,99 €/Monat | Unbegrenzte Aliasse, 2FA, Dark-Web-Überwachung, Tresore teilen, Notfallzugriff |
| **Pass Family** | 6,99 €/Monat | Pass-Plus-Funktionen für bis zu 6 Personen, Administrationskonsole zur Verwaltung der Familie |
| **Proton Unlimited** | 12,99 €/Monat | Proton Pass, Proton Mail, Proton Calendar, Proton VPN und Proton Drive |

---
# Fazit

## Antwort auf meine Leitfrage:
_Passwortmanager machen Passwörter sicherer, da sie starke Passwörter erzeugen und verschlüsselt speichern können. Allerdings entsteht ein Risiko, wenn man das Masterpasswort vergisst oder es in falsche Hände gerät. Deshalb ist ein Passwortmanager wie Proton Pass sinnvoll, solange man ihn richtig nutzt und sein Masterpasswort gut schützt._

**Vielen Dank für Ihre Aufmerksamkeit! Ich hoffe, Ihnen hat meine Präsentation zum Thema Passwortmanager gefallen.**

---
# Quellen
2. Folie:
   - [Was ist ein Passwortmanager?](https://nordvpn.com/de/password-manager/?nc=22797247436&ns=google&nm=cpc&nt=best%20vpn%20reddit&na=180867302765&gad_source=1&gad_campaignid=22797247436&gclid=EAIaIQobChMI7dSMm-bSlwMVYERBAh3njSxwEAAYAyAAEgJe7_D_BwE) vom 24.10.2026
3. Folie:
- NordPass:
   - [Nutzer weltweit](https://nordpass.com/de/password-manager/offer/) geöffnet am 25.10.2026
   - [Verschlüsselung](https://nordpass.com/de/features/xchacha20-encryption/) geöffnet am 25.10.2026
   - [Kostenloses Paket](https://nordpass.com/de/plans/) geöffnet am 25.10.2026
- Bitwarden:
   -  [Nutzer weltweit](https://finance.yahoo.com/technology/ai/articles/bitwarden-surpasses-15-million-users-160000253.html) geöffnet am 25.10.2026
   -   [Verschlüsselung](https://bitwarden.com/de-de/help/what-encryption-is-used/) geöffnet am 25.10.2026
   -   [Sitz](https://bitwarden.com/de-de/about/) geöffnet am 25.10.2026
   -   [Kostenloses Konto](https://bitwarden.com/go/start-free/) geöffnet am 25.10.2026
- Proton Pass:
   - [Nutzer weltweit](https://proton.me/de/pass) geöffnet am 25.10.2026
   - [Verschlüsselung](https://proton.me/de/pass/security) geöffnet am 25.10.2026
   - [Sitz](https://de.wikipedia.org/wiki/Proton_(Softwarehersteller)) geöffnet am 25.10.2026
   - [Kostenloses Konto](https://proton.me/de/pass/pricing) geöffnet am 25.10.2026
5. Folie
   - [Entwickler](https://de.wikipedia.org/wiki/Proton_(Softwarehersteller))  geöffnet am: 22.10.2026
   - [Markteinführung](https://de.wikipedia.org/wiki/Proton_(Softwarehersteller)#Proton_Pass)  geöffnet am: 22.10.2026
   - [Sicherheitsarchitektur](https://proton.me/de/blog/proton-pass-security-model)  geöffnet am: 22.10.2026
   - [Plattformen](https://proton.me/de/pass/download)  geöffnet am: 22.10.2026
6. Folie