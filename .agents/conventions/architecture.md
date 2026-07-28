# Architektur der Arbeitsumgebung

## Grundsatz

Jeder Arbeitsbereich ist ein Holon: eine eigenständige Einheit mit klarer Verantwortung, eigenem Kontext und eigener Arbeitsorganisation. Gleichzeitig kann er Teil eines größeren Holons sein.

Die Struktur trennt:

- **Woran gearbeitet wird:** sichtbare Dateien und Verzeichnisse im Arbeitsbereich
- **Wer arbeitet und wie:** Rollen, Prozesse, Regeln, Konventionen und arbeitssteuernde Informationen unter `.agents/`
- **Wie die Arbeit beginnt:** `AGENTS.md` als Einstieg, Orientierung und Routing

## Einordnung von Informationen

Eine Information gehört nach `.agents/`, wenn sie die Arbeit eines Agenten steuert. Ist sie selbst Gegenstand der Arbeit, gehört sie in den sichtbaren Arbeitsbereich.

Beispiele:

- Rollenidentität, Prozess und Qualitätsregeln gehören nach `.agents/`.
- Schnittstellenwissen über ein anderes Holon gehört nach `.agents/`.
- Entwürfe, Artikel, Gespräche und veröffentlichte Inhalte gehören in sichtbare Arbeitsverzeichnisse.
- Eine eigenständig gepflegte fachliche Wissenssammlung ist ein Arbeitsgegenstand oder ein eigenes Holon, nicht bloß Agentengedächtnis.

## Rollen

Eine Rolle beschreibt, wer für eine Aufgabe verantwortlich ist. Eine Prozessdatei beschreibt, was diese Rolle tut.

Jede Rolle:

- besitzt genau eine klar abgegrenzte Verantwortung,
- kennt ihre Eingaben, Ergebnisse und Grenzen,
- verwaltet ihre eigenen Prozesse und Erfahrungen,
- optimiert ausschließlich den eigenen Verantwortungsbereich.

Prozesse liegen bei der Rolle, die für ihre Ausführung verantwortlich ist. Übergreifende Prozesse gehören zur koordinierenden Rolle des übergeordneten Holons.

## Übergaben

Holons arbeiten über ihre jeweilige `AGENTS.md` zusammen. Ein übergeordnetes Holon verweist auf den Einstiegspunkt des zuständigen Holons, kennt aber weder dessen interne Rollen noch deren Prozesse.

Vor einer Übergabe liest der Koordinator die `AGENTS.md` des Ziel-Holons. Diese bestimmt selbst, welche Rolle und welcher Prozess für den Auftrag zuständig sind.

## Wiederholung

Gemeinsame Konventionen werden zentral innerhalb des jeweiligen Holons festgehalten. Entscheidende Verantwortungsgrenzen dürfen zusätzlich direkt in einer Rolle stehen, wenn sie dadurch ohne lange Verweiskette verständlich und zuverlässig ausführbar bleibt.
