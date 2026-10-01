# panzaknacker

**Linux- und Security-Automatisierung · Wien**

Ich entwickle Werkzeuge für Aufgaben aus meiner eigenen Research- und
Entwicklungsarbeit: Linux-Umgebungen wiederverwenden, Aktivitäten von
Softwareagenten nachvollziehen und Daten kontrolliert zwischen Systemen übernehmen.

Mein Hintergrund verbindet Softwareentwicklung im Team, Research-Automatisierung,
LLM-Orchestrierung und freiberufliche Sicherheitsprüfungen

**Technische Schwerpunkte:** Python · Go · Shell/Bash · Linux · TypeScript/Preact

## Ausgewählte Projekte

| Projekt | Aufgabe und Umsetzung | Einstieg |
| --- | --- | --- |
| **[dynamicflow](https://github.com/panzaknacker/dynamicflow)** | Wiederverwendbare Linux-Research-Umgebungen. Go-Control-Plane mit Profilen und zweckgebundenen Signaturen; unfertige Remote-Aktionen bleiben gesperrt. | [Ausprobieren](https://github.com/panzaknacker/dynamicflow#ausprobieren) · [Code](https://github.com/panzaknacker/dynamicflow#code) |
| **[plntir](https://github.com/panzaknacker/plntir)** | Agentenaktivität und Zusammenarbeit auf privaten Geräten. Go-/SQLite-Kern und TypeScript-Oberflächen; die Archivdemo prüft exakte Wiederherstellung und Manipulationsabwehr. | [Ausprobieren](https://github.com/panzaknacker/plntir#ausprobieren) · [Code](https://github.com/panzaknacker/plntir#code) |
| **[umzug-toolkit](https://github.com/panzaknacker/umzug-toolkit)** | Kontrollierte Linux-Datenübernahme. Python-Werkzeuge trennen Quarantäne, Freigabe und Restore; signierter Transport und Rollback ergänzen den Ablauf. | [Ausprobieren](https://github.com/panzaknacker/umzug-toolkit#ausprobieren) · [Code](https://github.com/panzaknacker/umzug-toolkit#code) |

Die Repositories zeigen Entwicklungsstände mit ausführbaren lokalen Beispielen,
Tests und benannten Grenzen. Remote-Integration und
Hardwarequalifikation sind eigene Arbeitsschritte. Die offene SELinux-Grenze
bei `umzug-toolkit` bleibt sichtbar. Die private Nutzung anderer Versionen
belegt keine Produktionsreife dieser Quellstände.

## Arbeitsweise

- Änderungen vor ihrer Anwendung prüfen und einen Weg zur Wiederherstellung vorsehen.
- Fehlerfälle und abgelehnte Eingaben ebenso prüfen wie den vorgesehenen Ablauf.
- Ergebnisse mit Befehlen, Umgebung und verbleibenden Grenzen festhalten.
