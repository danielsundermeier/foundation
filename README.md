# Foundation

Foundation verbindet eigenständige Holons und dient als Einstiegspunkt für gemeinsame Arbeitsprozesse.

Der aktuelle Standardprozess verarbeitet ein neues ChatGPT-Gespräch vollständig:

```text
Gespräch
    ↓
Foundation-Koordinator
    ↓
Blog-Koordinator
    ↓
veröffentlichter Artikel
    ↓
X-Koordinator
    ↓
terminierte Beiträge
```

Jeder Koordinator kennt nur den Ablauf seines eigenen Holons. Foundation verweist über die jeweilige `AGENTS.md` auf Blog und X; deren interne Rollen und Prozesse bleiben dort.

## Holon-Modell

```text
holon/
├── AGENTS.md       Einstieg und Routing
├── .agents/        Rollen, Prozesse, Regeln und arbeitssteuernde Informationen
└── …               Gegenstände, an denen gearbeitet wird
```

Eine Information gehört nach `.agents/`, wenn sie die Arbeit eines Agenten steuert. Ist sie selbst Gegenstand der Arbeit, gehört sie in den sichtbaren Arbeitsbereich.

## Foundation

- `AGENTS.md`: Einstieg und einziges Routing zum Foundation-Koordinator
- `.agents/conventions/`: Architekturkonvention
- `.agents/roles/coordinator/AGENTS.md`: Verantwortung des Koordinators
- `.agents/roles/coordinator/processes/process-conversation.md`: einziger Foundation-Prozess
- `.agents/roles/coordinator/feedback/`: Erfahrungen mit dem übergreifenden Gesprächsablauf
