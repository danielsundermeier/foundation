# Foundation

Foundation ist ein eigenständiges Holon und der Einstiegspunkt für gemeinsame Arbeitsprozesse.

## Arbeitsmodell

- Sichtbare Dateien und Verzeichnisse enthalten die Gegenstände, an denen gearbeitet wird.
- `.agents/` enthält, wer arbeitet und wie gearbeitet wird.
- `AGENTS.md` ist der Einstiegspunkt eines Holons und verweist auf die zuständige Rolle.

Die Architekturkonvention steht unter `.agents/conventions/architecture.md`.

## Zuständigkeit

Foundation versteht Eingangssignale und übergibt sie an das zuständige Holon. Foundation kennt nicht dessen interne Rollen oder Prozesse und erstellt keine Inhalte in dessen Verantwortung.

## Routing

| Signal oder Auftrag | Zuständige Rolle |
| --- | --- |
| Ein ChatGPT-Gespräch mit „Verarbeite dieses Gespräch“ oder einer gleichbedeutenden Formulierung | `.agents/roles/coordinator/AGENTS.md` |

Vor der Arbeit die verlinkte `AGENTS.md` vollständig lesen. Wenn kein Eintrag eindeutig passt, keine neue Prozesslogik erfinden, sondern um Klärung bitten.

## Grenzen

- Foundation verändert Knowledge und d15r nicht.
- Foundation schreibt, bewertet und veröffentlicht keine Blogartikel oder X-Beiträge.
- Foundation erstellt keine Commits und führt keinen Push aus.
- Bestehende, nicht zur Aufgabe gehörende Änderungen bleiben unangetastet.
