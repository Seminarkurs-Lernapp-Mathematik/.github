# Beitragen zu SLAM

Willkommen! Wir freuen uns über Beiträge zum SLAM-Projekt. Diese Richtlinien helfen dir, effektiv mitzumachen.

## Repositories

| Repo | Stack | Wofür |
|------|-------|-------|
| [`slam-app`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-app) | Flutter / Dart | Mobile & Web App |
| [`slam-backend`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-backend) | TypeScript / Cloudflare Workers | REST API |
| [`slam-docs`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-docs) | MkDocs | Dokumentation |
| [`slam-teacher`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-teacher) | React / Vite | Lehrer-Dashboard |

## Workflow

1. **Issue erstellen** — Beschreibe Bug oder Feature-Idee
2. **Fork & Branch** — Branch-Name: `feature/kurze-beschreibung` oder `fix/was-kaputt`
3. **Entwickeln** — Halte dich an die Code-Konventionen des jeweiligen Repos
4. **Pull Request** — Beschreibe was und warum, verlinke das Issue

## Code-Konventionen

**Flutter/Dart (`slam-app`)**
- `snake_case` für Dateinamen, `PascalCase` für Klassen, `camelCase` für Variablen
- Riverpod mit Code-Generation (`@riverpod`)
- Freezed für Modelle
- Nach Modelländerungen: `dart run build_runner build --delete-conflicting-outputs`

**TypeScript (`slam-backend`, `slam-teacher`)**
- Strikte TypeScript-Typen, kein `any`
- Async/await statt Callbacks

## Commit-Messages

```
feat: neue Funktion hinzugefügt
fix: Fehler in X behoben
docs: Dokumentation aktualisiert
refactor: Code umstrukturiert ohne Funktionsänderung
test: Tests hinzugefügt
chore: Build-Konfiguration angepasst
```

## Fragen?

Öffne einfach ein Issue — wir helfen gerne!
