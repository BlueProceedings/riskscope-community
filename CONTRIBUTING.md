# Beitragen

Danke, dass du deine Erfahrung teilen möchtest. Diese Seite erklärt, was wo hingehört und worauf wir achten.

## Bis zur ersten Version von RiskScope

Einreichungen von Vorlagen starten mit der ersten Version (geplant Januar 2027), weil Vorlagen dann als Datei aus
RiskScope exportiert und auf vertrauliche Angaben durchsucht werden. Bis dahin läuft alles über die
[Diskussionen](https://github.com/BlueProceedings/riskscope-community/discussions):

| Kategorie | Wofür |
|---|---|
| Ankündigungen | Neuigkeiten zu RiskScope und zur Community (nur Moderation) |
| Erfahrungen | Was bei der Arbeit mit Grundschutz++ funktioniert hat und was nicht |
| Fragen zur Methodik | Wie ist eine Anforderung, ein Begriff oder ein Schritt in Grundschutz++ gemeint? |
| Ideen und Wünsche | Was RiskScope können sollte |
| Vorlagen-Wünsche | Welche Blaupause oder Vorlage dir fehlt |

## Die Regel, die immer gilt

Keine echten Unternehmensdaten, keine Namen, keine vertraulichen Sicherheitsdetails. Konkret nicht hierher gehören:

- Namen von Personen, Institutionen, Dienstleistern oder Produkten in deiner Umgebung, wenn sie auf dich
  zurückführen;
- Hostnamen, IP-Adressen, Netzpläne, Konfigurationen, Zugangsdaten, Schlüssel;
- offene Schwachstellen, laufende Vorfälle, Ergebnisse von Audits oder Penetrationstests;
- alles, was dein Arbeitgeber oder deine Institution als vertraulich einstuft.

Schreib abstrahiert: „eine Kommune mittlerer Größe“, „ein Fachverfahren mit Bürgerkontakt“, „ein externer
Zahlungsdienstleister“. Wer versehentlich zu viel geteilt hat, kann den Beitrag selbst bearbeiten oder die
Moderation bitten, ihn zu entfernen.

## Gute Beiträge

- **Ein Thema je Beitrag**, mit einem Titel, der die Frage oder Erfahrung benennt.
- **Bezug zu Grundschutz++**, wenn möglich mit Praktik oder Anforderung.
- **Kontext ohne Identität**: Größe und Art der Institution, Rolle, Ausgangslage.
- **Ehrlich**: Was nicht funktioniert hat, ist oft am wertvollsten.

## Ab der ersten Version: Vorlagen einreichen

Jede eingereichte Datei beginnt mit Kopfdaten. Die Feldnamen sind englisch, die Inhalte deutsch:

```yaml
title: Kundenportal kommunaler Stadtwerke
kind: blueprint           # blueprint · information-domain-template · component-set-template · component-template
                          # report-template
grundschutzpp_reference: ""  # Praktik oder Anforderung
author: ""                # Name, Pseudonym oder leer (dann nur dein GitHub-Benutzername)
license: CC-BY-SA-4.0
version: 1.0.0
date: 2027-01-15
reviewed_by: ""           # wird von der Moderation gesetzt
```

Vorlagen werden in RiskScope erzeugt, dort mit vier Augen freigegeben und durch den Einreichungsassistenten auf
personenbezogene und vertrauliche Angaben durchsucht. Die Moderation prüft Inhalt, Rechte und Sicherheit nach bestem
Wissen und Gewissen, bevor sie per Pull Request aufgenommen werden. Details folgen mit
der ersten Version.

Mit einer Einreichung bestätigst du, dass du die Vorlage teilen darfst und dass sie keine personenbezogenen oder
vertraulichen Angaben enthält. Für ihren Inhalt bist du verantwortlich.

## Verantwortung

Auch eine sorgfältige Moderation kann Fehler nicht ausschließen. Jede Vorlage ist eine lesbare Textdatei, die du vor dem Import vollständig ansehen kannst. Der Import erzeugt nur einen lokalen Entwurf, den du selbst prüfst und freigibst. Für den Inhalt einer Einreichung ist verantwortlich, wer sie einreicht; ob eine Vorlage zur eigenen Institution passt, entscheidet, wer sie importiert. BlueProceedings stellt die Vorlagen unentgeltlich und ohne Gewähr bereit.

## Datenschutz beim Einreichen

Einreichungen laufen als Pull Request über GitHub. Dein GitHub-Benutzername, der Zeitpunkt und der Beitrag sind
öffentlich und bleiben in der Versionsgeschichte. Unter `author` wählst du, wie du genannt wirst; die Nennung entfernen
wir auf Wunsch. Einen Beitrag nehmen wir auf Wunsch aus dem aktuellen Stand, die Lizenz lässt sich aber nicht
widerrufen, und Kopien anderer bleiben bestehen. Wer für eine Institution einreicht, klärt vorher, ob die Vorlage
geteilt werden darf. Einzelheiten: [Datenschutzerklärung](https://blueproceedings.de/datenschutz/#community).

## Rechte und Lizenz

Mit einem Beitrag bestätigst du, dass du ihn teilen darfst und dass er unter CC BY-SA 4.0 veröffentlicht wird.
Übernimmst du Texte aus dem Grundschutz++-Katalog, nenne die Quelle.

## Verhalten

Es gilt der [Verhaltenskodex](CODE_OF_CONDUCT.md). Kritik an Inhalten ist willkommen, an Personen nicht.
