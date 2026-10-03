---
layout: default
title: Datenschutzerklärung
---

# Datenschutzerklärung — Schrittmacher

*Stand: 3. Oktober 2026*

## Kurzfassung

- **Deine Schritte und dein Gewicht bleiben auf deinem iPhone und deiner Apple Watch.** Schrittmacher liest sie aus Apple Health und zeigt sie dir an — sie verlassen dein Gerät nie.
- **Fortschrittsfotos bleiben nur auf deinem iPhone**, sind mit Face ID geschützt und landen weder in deiner Fotomediathek noch in Backups.
- **Es gibt keinen Server der App.** Der Entwickler hat keinerlei Zugriff auf deine Daten.
- **Kein Tracking, keine Analytics, keine Werbung, keine Drittanbieter-SDKs.**
- **Gesundheitsdaten werden nicht weitergegeben** und nicht für Werbung oder andere Zwecke genutzt.

---

## Verantwortlich für die Datenverarbeitung

Frederik Saxinger
E-Mail: [frederik.saxinger@yahoo.de](mailto:frederik.saxinger@yahoo.de)

## Welche Daten werden verarbeitet?

### Apple Health (HealthKit)

Mit deiner Erlaubnis **liest** Schrittmacher aus Apple Health:

- deine **Schrittzahl** — für Tagesfortschritt, Verlauf und Durchschnitte,
- dein **Körpergewicht**, deine **Größe** und – falls vorhanden – deinen **Körperfettanteil** — für Gewichtsverlauf, Trend, Veränderungen, BMI, die Prognose zu deinem Zielgewicht und die Körperfett-Schätzung,
- dein **Geburtsdatum** (nur das daraus berechnete Alter) und dein **biologisches Geschlecht** — ausschließlich für die Formeln der Körperfett-Schätzung.

Die Berechtigungen für den Gewichtsbereich werden erst erfragt, wenn du den Bereich „Gewicht“ öffnest. Andere Gesundheitsdaten werden nicht gelesen.

Wenn du in der App ein Gewicht einträgst, wird es mit deiner Erlaubnis **in Apple Health gespeichert**. Von Schrittmacher eingetragene Werte kannst du in der App wieder löschen.

Wenn du einen **Spaziergang** startest, beginnt die App eine Trainingssitzung („Gehen“). Das ist nötig, damit iOS die App bei gesperrtem iPhone weiterlaufen lässt und die Schrittzahl live aktualisiert werden kann. Dafür fragt iOS nach der Berechtigung, **Trainings zu schreiben**. Die Sitzung wird beim Beenden **verworfen** — es wird **kein Training in Apple Health gespeichert**.

### Bewegung & Fitness

Während eines Spaziergangs liest die App die Schritte des iPhone-Bewegungssensors (Schrittzähler), damit die Anzeige ohne Verzögerung mitzählt.

### Körpermaße

Bauch-, Hals- und Hüftumfang, die du eingibst, werden **nur im geschützten Speicher der App** abgelegt (nicht in Apple Health) und für die Schätzung deines Körperfettanteils und das Taille-zu-Größe-Verhältnis verwendet. Ist in Apple Health keine Größe oder kein Geschlecht hinterlegt, kannst du beides in der App angeben; es bleibt ebenfalls nur in der App.

### Fortschrittsfotos und Kamera

Im Bereich „Fotos“ kannst du mit der Kamera der App Fortschrittsfotos in vier Posen aufnehmen. Dafür fragt iOS nach der Kamera-Berechtigung.

- Die Fotos werden **ausschließlich im geschützten Speicher der App auf deinem iPhone** abgelegt, sind verschlüsselt, solange das Gerät gesperrt ist, und **von iCloud- und Computer-Backups ausgeschlossen**.
- Sie werden **nicht** in deiner Fotomediathek gespeichert und **nicht** übertragen.
- Wenn du die App löschst, werden auch die Fotos gelöscht. Einzelne Aufnahmetage kannst du in der App löschen.

### Face ID

Der Bereich „Fotos“ ist mit **Face ID** (ersatzweise mit deinem Gerätecode) geschützt. Die Abfrage startet erst, wenn du auf „Entsperren“ tippst, und der Bereich sperrt sich, sobald die App in den Hintergrund geht. Die Prüfung übernimmt iOS — Schrittmacher erhält **keinerlei biometrische Daten**, sondern nur die Information, ob die Entsperrung erfolgreich war.

### In der App gespeichert

Lokal auf deinem Gerät, im geschützten Speicher der App:

- dein Tagesziel, dein optionales Zielgewicht, deine Körpermaße und App-Einstellungen
- die heutige Schrittzahl als Zwischenstand für das Sperrbildschirm-Widget bzw. die Watch-Komplikation (Health-Daten sind bei gesperrtem Gerät verschlüsselt und für Widgets sonst nicht lesbar)
- ein technisches Protokoll der Spaziergänge (Zeitpunkte, Schrittzahlen, Statusmeldungen) zur Fehlersuche. Es ist auf wenige hundert Kilobyte begrenzt und wird **nicht** übertragen.

Es werden **keine** Standortdaten, Kontakte, Mikrofondaten oder Fotos aus deiner Fotomediathek verarbeitet. Es wird **keine Werbe-ID** ausgelesen.

### Freigabe für KI-Werkzeuge (MCP-Server, optional)

In den Einstellungen kannst du einen **MCP-Server** einschalten. Er ist standardmäßig **aus** und wird erst nach deiner ausdrücklichen Bestätigung aktiv. Dann können Programme **in deinem WLAN**, denen du Adresse und Schlüssel gibst – etwa Claude Code auf deinem Mac –, folgende Daten **lesen**: Schritte, Durchschnitte, Jahresbilanz, Gewicht mit Trend und Statistiken, geschätzte Körperzusammensetzung und Körpermaße. **Fortschrittsfotos werden nie freigegeben**, und über den Server lassen sich keine Daten ändern.

- Der Server läuft nur, solange die App geöffnet ist, und jede Anfrage braucht den geheimen Schlüssel.
- Welche Daten das verbundene Programm abruft und wohin es sie sendet, liegt bei diesem Programm. **Claude Code sendet abgerufene Daten zur Verarbeitung an Anthropic**; dafür gilt die Datenschutzerklärung von Anthropic: <https://www.anthropic.com/legal/privacy>
- Du kannst den Server jederzeit ausschalten oder einen neuen Schlüssel erzeugen, der alle bisherigen Verbindungen aussperrt.

**Schreibzugriff (optional, separat freizugeben):** Erst nach einer zweiten, eigenen Zustimmung können verbundene Programme Gewicht eintragen (in Apple Health) und von Schrittmacher eingetragene Werte löschen, Körpermaße eintragen und löschen sowie Tagesziel und Zielgewicht setzen. Standardmäßig muss jede einzelne Änderung auf dem iPhone bestätigt werden. Alle Änderungen werden in der App unter „Änderungen durch KI“ protokolliert und lassen sich dort rückgängig machen. Daten anderer Apps, Fotos und Freigaben können nicht verändert werden.

## Wo werden die Daten gespeichert?

Ausschließlich **lokal auf deinem iPhone bzw. deiner Apple Watch**. Die App nutzt keine eigene Cloud und keinen Server.

Deine Gesundheitsdaten selbst verwaltet **Apple Health**. Ob und wie diese zwischen deinen Geräten oder über iCloud synchronisiert werden, richtet sich nach deinen Einstellungen bei Apple:
<https://www.apple.com/legal/privacy/>

## Live-Aktivität, Widgets und Apple Watch

- Die **Live-Aktivität** während eines Spaziergangs wird lokal vom iPhone erzeugt und aktualisiert — es werden keine Push-Nachrichten über einen Server gesendet.
- **Sperrbildschirm-Widget** und **Watch-Komplikation** zeigen den lokal gespeicherten Zwischenstand bzw. lesen Apple Health direkt auf dem jeweiligen Gerät.
- Die **Watch-App** liest deine Schritte aus Apple Health auf der Uhr.

## Wer hat Zugriff?

Nur du. Der Entwickler hat **keinerlei Zugriff** auf deine Daten — es existiert kein Server, der diese Daten empfangen würde.

## Datenweitergabe

Ohne deine ausdrückliche Freigabe über den MCP-Server (siehe oben) findet **keine Weitergabe** an Dritte statt. Insbesondere:

- keine Werbenetzwerke
- keine Analytics- oder Crash-Reporting-Dienste
- keine Cloud-Speicherung
- keine externen APIs oder SDKs

Daten aus Apple Health werden gemäß den Vorgaben von Apple **nicht** für Werbung, Marketing oder Data-Mining verwendet und **nicht** an Dritte weitergegeben.

## Berechtigungen widerrufen

- **Apple Health:** Health-App → Profilbild → *Apps* → *Schrittmacher*
- **Bewegung & Fitness:** Einstellungen → *Datenschutz & Sicherheit* → *Bewegung & Fitness*
- **Live-Aktivitäten:** Einstellungen → *Schrittmacher* → *Live-Aktivitäten*
- **Kamera:** Einstellungen → *Schrittmacher* → *Kamera*
- **Face ID:** Einstellungen → *Face ID & Code* → *Andere Apps* → *Schrittmacher*

## Deine Rechte nach DSGVO

Du hast das Recht auf:

- **Auskunft** über deine Daten — alle von der App gespeicherten Daten sind in der App selbst einsehbar; deine Gesundheitsdaten in der Health-App.
- **Berichtigung** — Schrittdaten verwaltest du in der Health-App.
- **Löschung** — Fortschrittsfotos kannst du in der App einzeln löschen; beim Deinstallieren der App werden alle von ihr gespeicherten Daten inklusive der Fotos entfernt. Deine Gesundheitsdaten bleiben in Apple Health und können dort gelöscht werden.
- **Datenübertragbarkeit** — über den Export der Health-App (Profilbild → *Alle Gesundheitsdaten exportieren*).
- **Beschwerde bei einer Aufsichtsbehörde** (z. B. Österreichische Datenschutzbehörde, <https://www.dsb.gv.at>).

## Änderungen dieser Datenschutzerklärung

Diese Erklärung kann in zukünftigen App-Versionen angepasst werden. Die jeweils aktuelle Fassung ist unter
<https://frederiksaxinger.github.io/schrittmacher-privacy/> einsehbar.

---

[Support →](support/)
