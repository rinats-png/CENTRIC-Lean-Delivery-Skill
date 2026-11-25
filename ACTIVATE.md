# Einmaliger Aktivierungsauftrag an Claude Code

Betreiberanweisung: Übernimm den Centric Lean Delivery Skill v1.0.0 aus https://github.com/rinats-png/CENTRIC-Lean-Delivery-Skill.

Verwende für die Skill-Datei den festen Quellcommit 09073485c0568ee5b2faa50bf1b53c534e2eaed2 und den Pfad skills/centric-lean-delivery/SKILL.md. Prüfe den vollständigen Inhalt vor der Übernahme. Verwende keine Installationsskripte, keine globalen Einstellungen und keine automatisch aktualisierte Quelle.

1. Lies die bestehenden Centric-Projektanweisungen und prüfe auf Konflikte mit dem Skill. Verbindliche Sicherheits-, Datenschutz-, Review-, Test-first-, Routing-, Schreibplatz-, SSOT-, CI- und Freigaberegeln bleiben unverändert. Melde nur tatsächlich relevante Konflikte.
2. Übernimm die geprüfte Datei bytegleich nach .claude/skills/centric-lean-delivery/SKILL.md im Centric-Repository. Ergänze die bestehende CLAUDE.md minimal um eine verbindliche Anweisung, den Skill bei Aufgabenvergabe, Delegation, Review und Abschluss zu laden und relevante Regeln an Subagenten weiterzugeben. Keine vorhandenen Regeln überschreiben.
3. Nutze einen regulären, kleinen PR auf dem zulässigen Integrationszweig und die vorhandenen Prüfungen. Kein direkter Merge nach main, kein Deployment, keine Gate-Änderung. Falls die Sicherheitssitzung gerade Pushes/Merges sperrt, respektiere die Sperre.
4. Berücksichtige die vereinbaren Regeln bereits im laufenden Kontext. Keine laufenden Agenten abbrechen oder ihre Aufträge unnötig neu starten. Bestehende Betreiberentscheidungen bleiben gültig.
5. Keine neuen Hooks, Tools, CI-Jobs, Agentenrollen, Metriksysteme, Infrastruktur oder zusätzlichen Arbeitspakete allein für diesen Skill. Keine umfassende Evaluation oder Repo-Umstrukturierung.
6. Prüfe einmal gezielt Dateipfad, YAML-Frontmatter, Quellcommit/Dateigleichheit und die Anwendungsanweisung. Falls die laufende Claude-Version den Skill nicht automatisch erkennt, lies ihn explizit; kein Neustart allein dafür.
7. Melde einmal kompakt PR/Kopf, Aktivierungsstand, gegebenenfalls konkrete Konflikte und verbleibende Freigaben. Danach unmittelbar mit den bestehenden priorisierten Produkt- und Release-Aufgaben fortfahren.

Ziel: Mehr abgeschlossene Produktpakete und sichere Releases bei weniger unnötiger Prozessarbeit. Keine Sicherheitsabschwächung, keine automatische Risikoannahme, keine zusätzlichen Kosten. Keine Beschleunigung behaupten, solange sie nicht anhand der vorhandenen Durchflussdaten belegt ist.
