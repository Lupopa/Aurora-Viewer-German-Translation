# Aurora Viewer – Deutsche Übersetzung: QA3-Prüfbericht

**Prüfstand:** 16. November 2026  
**Aurora-Quellstand:** [`f3aadd8153f82fa0f2e3e8bc4b7b53e68acc962a`](https://github.com/Aurora-Viewer/Aurora-Viewer/tree/f3aadd8153f82fa0f2e3e8bc4b7b53e68acc962a)  
**Status der Sprachdatei:** Community-Vorabversion; weitere sprachliche Korrekturen möglich

## Ergebnisse der QA3-Prüfung

Die folgenden Ergebnisse stammen aus dem bei QA3 erzeugten Prüfbericht von OpenAI Codex:

- **14.432 Nachrichtenschlüssel** für den genannten Aurora-Quellstand.
- **29 Schlüssel gegenüber QA2 geändert:** alle 18 dokumentierten Befunde sowie 11 entsprechende Stellen in verwandten Dialogen und Reglern.
- **Fluent-Kontrollen bestanden:** Parser, Schlüsselreihenfolge, Attribute, Variablen, Referenzen, Platzhalter, Selektoren und Varianten wurden mit der zugehörigen englischen Referenz abgeglichen.
- **14.773 Fluent-Formatierungen** laut QA3-Prüfbericht ohne Fehler.
- **13 offizielle Rust-Tests** des isolierten Sprachmoduls `aurora-i18n` laut QA3-Prüfbericht offline bestanden.

## SHA-256-Prüfsummen der QA3-Dateien

| Datei | SHA-256 |
| --- | --- |
| Englische Referenz `en.ftl` | `6bc0a93930bbb6c51af7c599c46e1bcb49c703b0d71f31a32579a7ff1c2e1b07` |
| Deutsche QA3-Datei `de.ftl` | `1447599cc02adb78bf912158c2f831c208ca8b8404ab57771cff7a80429b7931` |

## Abgrenzung und weiterer Teststand

**Zum Zeitpunkt dieser QA3-Prüfung** war der vollständige Viewer noch nicht kompiliert oder gestartet worden. Der Bericht belegt ausschließlich die oben genannten Prüfungen der Sprachdatei und des isolierten Sprachmoduls.

**Späterer Projektstand (nach QA3):** Ein eigener Windows-x64-Build mit deutscher Sprachunterstützung wurde anschließend erstellt und von Micha persönlich gestartet. Diese späteren Schritte sind **nicht** Bestandteil der QA3-Testresultate; daraus lässt sich keine vollständige Funktions- oder Sprachqualitätsprüfung ableiten.

Die sprachliche Stichprobe deckt nicht sämtliche möglichen Stil- und Übersetzungsfehler ab. Wortwahl, Textlängen und Darstellung einzelner Bedienelemente – insbesondere der Avatarregler – sind weiter im laufenden Praxistest zu überprüfen.

## Herkunft und Hinweise

Dies ist ein **unabhängiges Community-Übersetzungsprojekt** von Micha (Second Life: lupopa Grau), mit Unterstützung durch ChatGPT und OpenAI Codex. Die QA3-Tests wurden laut dem ursprünglichen Codex-Prüfbericht ausgeführt; dieser öffentliche Bericht gibt die Ergebnisse wieder und behauptet keine zusätzliche unabhängige Testausführung.

Offizielles Aurora-Projekt: https://github.com/Aurora-Viewer/Aurora-Viewer  
Community-Diskussion: https://github.com/Aurora-Viewer/Aurora-Viewer/discussions/3906
