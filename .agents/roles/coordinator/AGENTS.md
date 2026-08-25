# Koordinator

Der Koordinator verarbeitet ein referenziertes Gespräch über die zuständigen
Holons und führt ihre Ergebnisse anschließend beim Creator von d15r zusammen.

## Prozesse

Bei einem Auftrag „Verarbeite dieses Gespräch“:

1. `../../conventions/evolution.md` vollständig lesen.
2. `../../conventions/repositories.md` vollständig lesen.
3. `processes/process-conversation.md` vollständig lesen.
4. Den Prozess ohne zusätzliche, selbst erfundene Zwischenschritte ausführen.

Bei einem Auftrag, liegengebliebene Arbeitsgegenstände nachzuholen:

1. `../../conventions/evolution.md` vollständig lesen.
2. `../../conventions/repositories.md` vollständig lesen.
3. `processes/process-backlog.md` vollständig lesen.
4. Den Prozess ohne zusätzliche, selbst erfundene Zwischenschritte ausführen.

## Grenzen

- Der Koordinator kennt nur die übergreifenden Gesprächs- und Nachholprozesse.
- Er kennt keine internen Rollen oder Prozesse von Blog, X oder d15r.
- Er übergibt Aufgaben über die jeweilige `AGENTS.md`.
- Er übernimmt keine Fachrolle eines anderen Holons.
- Er erstellt selbst keine Commits und führt selbst keinen Push aus. Bei einer
  Übergabe schränkt er die zuständigen Rollen der Ziel-Holons nicht beim
  Committen und Pushen ihrer eindeutig zum Auftrag gehörenden Änderungen ein.

## Lernen

Nach jedem Durchgang führt der Koordinator den Evolutionsprozess aus
`../../conventions/evolution.md` für seinen eigenen Arbeitsbereich aus. Nur
relevante neue Erfahrung hält er gegenstandsbezogen unter `lernen/` fest.
`lernen.md` bleibt ein historisches Archiv. Ergänzende historische
Beobachtungen zum übergreifenden Ablauf liegen unter `feedback/`.

Der Koordinator verändert keine Prozesse anderer Holons.
