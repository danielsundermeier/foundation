# Gespräch verarbeiten

## Eingang

Ein vollständiges ChatGPT-Gespräch ist im aktuellen Codex-Task referenziert.

## Ablauf

1. Das referenzierte Gespräch vollständig erfassen.
2. Die `AGENTS.md` unter `/Users/danielsundermeier/code/danielsundermeier/blog/AGENTS.md` vollständig lesen.
3. Das Gespräch mit dem Auftrag, es vollständig zu verarbeiten, an das Blog-Holon übergeben.
4. Endet Blog mit einem veröffentlichten Artikel, die `AGENTS.md` unter `/Users/danielsundermeier/code/danielsundermeier/x/AGENTS.md` vollständig lesen.
5. Den veröffentlichten Artikel mit dem Auftrag, ihn vollständig zu verarbeiten, an das X-Holon übergeben.
6. Endet Blog mit einem blockierten Entwurf, X nicht aufrufen.
7. Endet X blockiert, den bereits veröffentlichten Blogartikel unverändert lassen.
8. Unabhängig vom Status von Blog oder X die `AGENTS.md` unter
   `/Users/danielsundermeier/code/danielsundermeier/d15r/AGENTS.md`
   vollständig lesen.
9. Das ursprüngliche Gespräch als Hauptinput an d15r übergeben. Vorhandene
   Ergebnisse von Blog und X einschließlich ihrer Creator-Rückgaben als
   abgeleitete, eindeutig miteinander verbundene Quellenlinie mitgeben.
10. d15r mit dem Auftrag aufrufen, Gespräch und Rückgaben über die zuständige
    Rolle ausschließlich in die gemeinsame Identität einfließen zu lassen.
    Die Auswahl und Ausführung des internen Identitätsprozesses bestimmt d15r.
11. Den eigenen Durchgang nach `../../../conventions/evolution.md` auswerten
    und nur relevante neue Erfahrung gegenstandsbezogen unter `../lernen/`
    festhalten.
12. Bei Bedarf ergänzende historische Beobachtungen unter `../feedback/` festhalten.
13. Die Ergebnisse oder konkreten Blocker aller Übergaben melden.

## Grenzen

- Die Auswahl und Ausführung interner Rollen bestimmt ausschließlich die `AGENTS.md` des jeweiligen Ziel-Holons.
- Keine direkten Änderungen an Knowledge oder d15r. Änderungen in d15r nimmt
  ausschließlich dessen zuständige Rolle nach der Übergabe vor.
- Keine direkte Veröffentlichung über eine Plattform-API.
- Foundation erstellt keine eigenen Commits oder Pushes. Die zuständigen Rollen
  von Blog, X und d15r dürfen die eindeutig zu diesem Zyklus gehörenden
  Änderungen nach den Prozessen ihres Holons committen und ohne Force-Push
  pushen. Diese Berechtigung wird in jeder Übergabe ausdrücklich mitgegeben.
- Die d15r-Übergabe darf aktuell nur die Identität verändern. Sie beauftragt
  keine sichtbaren oder technischen Änderungen an der Webseite.
