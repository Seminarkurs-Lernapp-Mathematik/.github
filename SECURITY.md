# Security Policy

## Unterstützte Versionen

| Version | Support |
|---------|---------|
| `main` branch | ✅ Aktiv unterstützt |
| Ältere Releases | ❌ Kein Support |

## Sicherheitslücke melden

**Bitte melde Sicherheitslücken NICHT als öffentliches GitHub Issue.**

Sende stattdessen eine E-Mail an das Projektteam. Wir werden innerhalb von 48 Stunden antworten und gemeinsam eine Lösung erarbeiten.

## Bekannte Sicherheitsmaßnahmen

- Firebase Authentication mit Domain-Einschränkung (`@mvl-gym.de`)
- Alle API-Endpunkte erfordern gültige JWT-Tokens
- Cloudflare Rate-Limiting auf allen Backend-Endpunkten
- Keine Speicherung von API-Keys im Client
- Firestore Security Rules schützen Nutzerdaten
