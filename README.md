# CENTRIC Lean Delivery Skill

Version 1.0.0 · Deutsch · Claude Code

Ein kompakter, projektspezifischer Anti-Overengineering-Skill für Centric. Ziel ist die Fertigstellung nutzbarer, sicherer Produktinkremente, nicht die Maximierung von Prozessen, PRs oder Dokumentation.

## Inhalt
- [SKILL.md](skills/centric-lean-delivery/SKILL.md): vollständige Arbeitsregeln.
- [Aktivierungsprompt](ACTIVATE.md): einmaliger Auftrag an den bestehenden Claude-Koordinator.

## Installation
Den Skill aus einem überprüften, festen Commit dieses Repositorys in das Centric-Projekt unter `.claude/skills/centric-lean-delivery/SKILL.md` übernehmen. Nicht als globale Benutzereinstellung installieren. Die bestehende `CLAUDE.md` minimal um eine verbindliche Anwendungsanweisung ergänzen; bestehende Anweisungen nicht überschreiben. Vorhandene Regeln bei der Übernahme prüfen und bei Konflikten nicht abschwächen.

Die Installation erfolgt über den vorhandenen Centric-PR- und Review-Prozess, auf dessen zulässigem Integrationszweig. Keine direkten Änderungen an main oder Produktion. Bis zur Integration kann der Koordinator die Regeln ausdrücklich als Betreiberanweisung im aktuellen Kontext berücksichtigen.

Keine Laufzeitabhängigkeiten, Hooks, zusätzlichen Testsuiten, Cloud-Dienste oder automatisch nachgeladenen Inhalte. Updates ausschließlich bewusst über einen neuen geprüften Commit übernehmen.

## Anwendung
Bei Aufgabenvergabe, Review und Abschluss die relevanten Regeln anwenden. Der Koordinator übergibt sie an Subagenten; die automatische Skill-Erkennung allein ist keine Garantie. Bei Bedarf im Projekt mit /centric-lean-delivery aufrufen, sofern die installierte Claude-Code-Version den Skill erkennt.

## Akzeptanzbeispiele
| Situation | Erwartetes Verhalten |
|---|---|
| Kleiner Dokumentationsfehler | Kleine Korrektur, bestehende Pflichtprüfung, kein neues Framework |
| Authentisierungsfehler | Vollständiger bestehender Sicherheitsprozess, keine Abkürzung |
| CI ist grün, Test wurde übersprungen | Kein erfolgreicher Nachweis für diesen Test |
| Optionales Refactoring nach erfülltem Auftrag | Nicht ungefragt ausführen |
| Neues Backup-Werkzeug vorgeschlagen | Vorhandene Infrastruktur auf Gleichwertigkeit prüfen; kein Kauf ohne Freigabe |
| Review entdeckt tatsächlichen Release-Blocker | Erfassen und bearbeiten; nicht umstufen |
| Lokale CPU am Limit | Schwere Prüfungen zulässig auslagern, keine aktiven Prozesse abbrechen |
| Alle Kriterien erfüllt | Abschluss und nächstes priorisiertes Paket |

## Grenzen
Der Skill ist eine Verhaltensanweisung, keine technisch erzwungene Sicherheitskontrolle. Seine Wirkung auf Durchsatz ist nicht empirisch belegt. Verbindliche Prüfungen, Freigaben, Schutzmechanismen und Betreiberentscheidungen bleiben unverändert.

## Methodische Inspiration
Eigenständig formuliert für Centric, auf Basis allgemeiner KISS-/YAGNI-Prinzipien und risikoadäquater Prozessbudgets. Weiterführende Referenzen: [Karpathy Guidelines](https://github.com/multica-ai/andrej-karpathy-skills), [AI Engineering Skills](https://github.com/tmusser/ai-engineering-skills), [Agent Workflow](https://github.com/Chrike/coding-agent-skills), [Code Simplification](https://github.com/addyosmani/agent-skills). Keine dieser Sammlungen muss installiert werden.
