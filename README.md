# panzaknacker

**Linux- und Security-Automatisierung · Wien**

Ich entwickle Werkzeuge für Aufgaben aus meiner eigenen Research- und
Entwicklungsarbeit: Linux-Umgebungen wiederverwenden, Aktivitäten von
Softwareagenten nachvollziehen und Daten kontrolliert zwischen Systemen übernehmen.

Mein Hintergrund verbindet Softwareentwicklung im Team, Research-Automatisierung,
LLM-Orchestrierung und freiberufliche Sicherheitsprüfungen. Ich interessiere mich
für Junior-Aufgaben in Softwareentwicklung, Linux-Infrastruktur und IT-Security.

**Technische Schwerpunkte:** Python · Go · Shell/Bash · Linux · TypeScript/Preact

## Ausgewählte Projekte

| Projekt | Aufgabe und Umsetzung | Einstieg |
| --- | --- | --- |
| **[dynamicflow](https://github.com/panzaknacker/dynamicflow)** | Wiederverwendbare Linux-Research-Umgebungen. Go-Control-Plane mit Profilen und zweckgebundenen Signaturen; unfertige Remote-Aktionen bleiben gesperrt. | [Demo](https://github.com/panzaknacker/dynamicflow/blob/main/docs/DEMO.md) · [Prüfnachweise](https://github.com/panzaknacker/dynamicflow/blob/main/docs/VERIFICATION.md) |
| **[plntir](https://github.com/panzaknacker/plntir)** | Agentenaktivität und Zusammenarbeit auf privaten Geräten. Go-/SQLite-Kern und TypeScript-Oberflächen; die Archivdemo prüft exakte Wiederherstellung und Manipulationsabwehr. | [Archivdemo](https://github.com/panzaknacker/plntir/blob/main/docs/DEMO.md) · [Komponentenstand](https://github.com/panzaknacker/plntir/blob/main/PROJECT_STATUS.md) |
| **[umzug-toolkit](https://github.com/panzaknacker/umzug-toolkit)** | Kontrollierte Linux-Datenübernahme. Python-Werkzeuge trennen Quarantäne, Freigabe und Restore; signierter Transport und Rollback ergänzen den Ablauf. | [Demo](https://github.com/panzaknacker/umzug-toolkit/blob/main/docs/DEMO.md) · [Prüfstand](https://github.com/panzaknacker/umzug-toolkit/blob/main/docs/VALIDATION.md) |

Die Repositories zeigen Entwicklungsstände mit ausführbaren lokalen Beispielen,
Prüfprotokollen und dokumentierten Grenzen. Remote-Integration und
Hardwarequalifikation sind eigene Arbeitsschritte. Die offene SELinux-Grenze
bei `umzug-toolkit` bleibt sichtbar. Die private Nutzung anderer Versionen
belegt keine Produktionsreife dieser Quellstände.

## Arbeitsweise

- Änderungen vor ihrer Anwendung prüfen und einen Weg zur Wiederherstellung vorsehen.
- Fehlerfälle und abgelehnte Eingaben ebenso prüfen wie den vorgesehenen Ablauf.
- Ergebnisse mit Befehlen, Umgebung und verbleibenden Grenzen festhalten.
