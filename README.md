<p align="center">
  <img src=".github/logo.svg" width="72" height="72" alt="">
</p>

<h1 align="center">RiskScope Community</h1>

<p align="center"><b>Gute Vorlagen entstehen in der Praxis. Teilen wir sie.</b><br>
Vorlagen, Berichtsvorlagen und Erfahrungen für die Arbeit mit Grundschutz++</p>

<p align="center">
  <a href="https://github.com/BlueProceedings/riskscope-community/discussions"><b>Zu den Diskussionen</b></a> ·
  <a href="https://blueproceedings.de/community/">Community auf der Website</a> ·
  <a href="https://github.com/BlueProceedings/riskscope">RiskScope</a>
</p>

---

Was eine Institution einmal sauber modelliert hat, muss die nächste nicht neu erfinden. Hier sammeln wir, was sich
in der ISMS-Praxis mit Grundschutz++ bewährt hat: vor der Aufnahme moderiert und frei nutzbar unter
CC BY-SA 4.0, wie der Grundschutz++-Katalog des BSI selbst.

| Jetzt | Ab der ersten Version von RiskScope (geplant Januar 2027) |
|---|---|
| **Diskussionen sind offen**: Erfahrungen, Fragen zur Methodik, Ideen und Wünsche für Vorlagen | Einreichungen von Vorlagen als Datei, die RiskScope direkt importiert |

## Eine Regel vorab

> **Keine echten Unternehmensdaten, keine Namen, keine vertraulichen Sicherheitsdetails.**
> Beschreibe Vorlagen und Erfahrungen so, dass niemand auf deine Institution schließen kann: keine Hostnamen,
> IP-Adressen, Dienstleisternamen, Schwachstellen oder Zugangsdaten. Im Zweifel weglassen.

Gerade im ISMS-Umfeld ist das die größte Gefahr für Beitragende. Beiträge, die diese Regel verletzen, entfernt die
Moderation ohne Rückfrage.

## Was hier entsteht

| Ordner | Art | Format |
|---|---|---|
| [`blueprints/`](blueprints/) — Blaupausen | Anforderungsauswahl für eine Art von Informationsverbund: Ausschlüsse mit Begründung, Ergänzungen, Parameterwerte | OSCAL-Profil |
| [`information-domain-templates/`](information-domain-templates/) — Informationsverbundvorlagen | Referenz-Sicherheitskonzept: welche Komponenten und Anforderungen für eine Art von Informationsverbund relevant sind | Vorlagenpaket |
| [`component-set-templates/`](component-set-templates/) — Komponentensatz-Vorlagen | Ein bewährter Stack aus mehreren Komponenten, etwa eine Virtualisierungsumgebung oder ein Portal mit Anmeldung, WAF und Datenbank | Vorlagenpaket |
| [`component-templates/`](component-templates/) — Komponentenvorlagen | Eine wiederverwendbare Komponente mit Vorbelegungen, typisch die virtuelle Maschine im eigenen Virtualisierungscluster | Vorlagenpaket |
| [`report-templates/`](report-templates/) — Berichtsvorlagen | Gliederungen und Textbausteine, etwa für Managementbewertung oder Quartalsbericht | Dokument |
| [Diskussionen](https://github.com/BlueProceedings/riskscope-community/discussions) | Erfahrungen: was funktioniert hat und was nicht | Diskussion |

Die Ordner füllen sich mit der ersten Version. Schon jetzt hilft es, in
[Vorlagen-Wünsche](https://github.com/BlueProceedings/riskscope-community/discussions) zu sagen, was du brauchst.

## So wird eine Vorlage eingereicht (ab der ersten Version)

1. **Lokal freigeben:** Nur eine mit vier Augen freigegebene Vorlage kann eingereicht werden.
2. **Redaktion prüfen:** RiskScope sucht in Freitexten nach Namen, Kontaktdaten, IP-Adressen, Hostnamen und
   Geheimnissen. Jede Fundstelle braucht eine Entscheidung.
3. **Paket erzeugen:** mit Lizenz, Rechteerklärung und maschinenlesbarem Prüfbericht.
4. **Moderation:** Die Einreichung läuft als Pull Request in diesem Repository. Die Moderation prüft Inhalt, Rechte und Sicherheit
   nach bestem Wissen und Gewissen.
5. **Signiert veröffentlichen:** Angenommene Pakete werden signiert, damit ihre Herkunft nachvollziehbar ist. Beim Import
   entsteht immer ein lokaler Entwurf, den du selbst prüfst und freigibst.

Die automatische Suche nach vertraulichen Angaben ist eine Hilfe, keine Garantie.

## Verantwortung

Auch eine sorgfältige Moderation kann Fehler nicht ausschließen. Jede Vorlage ist eine lesbare Textdatei, die du vor dem Import vollständig ansehen kannst. Der Import erzeugt nur einen lokalen Entwurf, den du selbst prüfst und freigibst. Für den Inhalt einer Einreichung ist verantwortlich, wer sie einreicht; ob eine Vorlage zur eigenen Institution passt, entscheidet, wer sie importiert. BlueProceedings stellt die Vorlagen unentgeltlich und ohne Gewähr bereit.

Notfallszenarien und Übungsdrehbücher teilen wir bewusst nicht als Vorlage: In RiskScope beziehen sie sich auf die eigenen
Prozesse, Komponenten und Standorte. Erfahrungen damit sind in den Diskussionen willkommen.

## Was beim Einreichen mit deinen Daten passiert

- **Öffentlich über GitHub:** Für einen Pull Request brauchst du ein GitHub-Konto. Benutzername, Zeitpunkt und Beitrag
  sind öffentlich sichtbar. Für dein Konto ist GitHub verantwortlich.
- **Nennung nach deiner Wahl:** CC BY-SA 4.0 sieht eine Nennung vor. Du entscheidest, ob dein Name, ein Pseudonym oder
  nur dein GitHub-Benutzername erscheint, und kannst die Nennung später entfernen lassen.
- **Keine Daten Dritter:** Vorlagen enthalten keine Namen, Kontaktdaten oder Angaben, die auf Personen oder deine
  Institution schließen lassen. Wer für eine Institution einreicht, klärt vorher, ob die Vorlage geteilt werden darf.
- **Rücknahme mit Grenzen:** Auf Wunsch nehmen wir einen Beitrag aus dem aktuellen Stand. Die Lizenz lässt sich nicht
  widerrufen, und die Versionsgeschichte sowie bereits erstellte Kopien (Forks) bleiben bestehen.

Einzelheiten und Rechtsgrundlagen: [Datenschutzerklärung](https://blueproceedings.de/datenschutz/#community).

## Mitmachen

- Lies [CONTRIBUTING.md](CONTRIBUTING.md) und den [Verhaltenskodex](CODE_OF_CONDUCT.md).
- Stell dich gern in den [Diskussionen](https://github.com/BlueProceedings/riskscope-community/discussions) vor:
  Rolle, Art der Institution und woran du gerade arbeitest, ohne Namen.

## Lizenz

Alle Inhalte in diesem Repository stehen unter
[Creative Commons Namensnennung – Weitergabe unter gleichen Bedingungen 4.0 International (CC BY-SA 4.0)](LICENSE),
sofern bei einem Beitrag nichts anderes angegeben ist. Inhalte, die Texte aus dem Grundschutz++-Katalog des BSI
übernehmen, nennen die Quelle.

## Einordnung

Die Community gehört zu RiskScope, einem unabhängigen Projekt von BlueProceedings, Bonn. Sie ist kein Angebot des
BSI. Beiträge unterstützen die Vorbereitung auf Grundschutz++; sie sagen nichts über Konformität oder Zertifizierung
aus.

[Impressum](https://blueproceedings.de/impressum/) · [Datenschutz](https://blueproceedings.de/datenschutz/)
