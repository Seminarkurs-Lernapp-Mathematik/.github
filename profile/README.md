<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Seminarkurs-Lernapp-Mathematik/.github/main/assets/banner-dark.svg">
  <img alt="SLAM – Seminarkurs Lernapp Mathematik" src="https://raw.githubusercontent.com/Seminarkurs-Lernapp-Mathematik/.github/main/assets/banner-light.svg" width="100%">
</picture>

# 🧠 SLAM — Seminarkurs Lernapp Mathematik

**KI-gestützte Mathematik-Lernplattform für die gymnasiale Oberstufe**

<br/>

[![App](https://img.shields.io/badge/App-app.learn--smart.app-6366f1?style=for-the-badge&logo=flutter&logoColor=white)](https://app.learn-smart.app)
[![API](https://img.shields.io/badge/API-api.learn--smart.app-f59e0b?style=for-the-badge&logo=cloudflare&logoColor=white)](https://api.learn-smart.app)
[![Docs](https://img.shields.io/badge/Docs-docs.learn--smart.app-10b981?style=for-the-badge&logo=gitbook&logoColor=white)](https://docs.learn-smart.app)
[![Website](https://img.shields.io/badge/Website-learn--smart.app-3b82f6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://learn-smart.app)

</div>

---

## 🚀 Was ist SLAM?

SLAM ist eine vollständige, KI-gestützte Lernplattform, die Mathematikunterricht personalisiert und interaktiv macht. Die App generiert adaptive Fragen, wertet Antworten intelligent aus, visualisiert Konzepte mit GeoGebra und motiviert durch ein Gamification-System mit XP, Coins und Streaks.

```
📱 Schüler lernen    →   🤖 KI analysiert Fortschritt   →   📊 Lehrer behalten den Überblick
     adaptiv                  & passt Schwierigkeit an              über ihre Klassen
```

---

## 📦 Repositories

<table>
<tr>
<td width="50%" valign="top">

### [`slam-app`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-app) 📱

**Flutter Mobile & Web App**

Die Haupt-Lernapp für Schüler. Läuft nativ auf iOS & Android und als Progressive Web App.

**Highlights:**
- Adaptiver Live-Feed mit KI-generierten Aufgaben
- GeoGebra-Visualisierungen direkt in der App
- KI-Labor: interaktive Mini-Apps on-the-fly
- Gamification: XP, Coins, Streaks, Shop
- Offline-first mit mehrstufigem Caching (Hive + Firestore)
- LaTeX-Rendering für mathematische Ausdrücke

[![Flutter](https://img.shields.io/badge/Flutter-3.27+-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.6+-0175C2?logo=dart)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com)
[![Riverpod](https://img.shields.io/badge/Riverpod-2.6+-00BCD4)](https://riverpod.dev)

→ **[app.learn-smart.app](https://app.learn-smart.app)**

</td>
<td width="50%" valign="top">

### [`slam-backend`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-backend) ⚡

**Cloudflare Workers API**

Edge-deployed REST API auf Cloudflare Workers. Koordiniert alle KI-Anfragen und stellt Lehrer-Endpunkte bereit.

**Endpunkte:**
- `POST /api/generate-questions` — Adaptive Aufgabengenerierung
- `POST /api/evaluate-answer` — KI-Bewertung mit Feedback
- `POST /api/custom-hint` — Personalisierte Hilfestellung
- `POST /api/generate-geogebra` — Dynamische Visualisierungen
- `POST /api/generate-mini-app` — KI-Labor Mini-Apps
- `/teacher/*` — Analytics & Klassenverwaltung

[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript)](https://typescriptlang.org)
[![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F6821F?logo=cloudflare&logoColor=white)](https://workers.cloudflare.com)
[![Hono](https://img.shields.io/badge/Hono-E36002)](https://hono.dev)
[![Claude](https://img.shields.io/badge/Claude_AI-Sonnet_4.6-8B5CF6)](https://anthropic.com)

→ **[api.learn-smart.app](https://api.learn-smart.app)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [`slam-docs`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-docs) 📚

**Technische Dokumentation**

Vollständige Entwickler-Dokumentation gebaut mit MkDocs. Architektur, API-Referenz, Deployment-Guides und Beitragsrichtlinien.

**Inhalt:**
- Architekturübersicht & Design-Entscheidungen
- Vollständige API-Referenz aller Endpunkte
- Flutter-App Entwicklungsguide
- Firebase & Cloudflare Deployment
- Gamification-System Dokumentation

[![MkDocs](https://img.shields.io/badge/MkDocs-526CFE?logo=materialformkdocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-181717?logo=github)](https://pages.github.com)

→ **[docs.learn-smart.app](https://docs.learn-smart.app)**

</td>
<td width="50%" valign="top">

### [`slam-teacher`](https://github.com/Seminarkurs-Lernapp-Mathematik/slam-teacher) 👩‍🏫

**Lehrer-Dashboard**

Web-Oberfläche für Lehrkräfte zur Verwaltung von Klassen, Überwachung des Lernfortschritts und Festlegung von Lernzielen.

**Features:**
- Echtzeit-Klassenuebersicht & Fortschritts-Analytics
- Individuelle Schüler-Auswertungen
- Lernziele & Aufgaben-Zuweisung
- Leistungsvergleiche & Trend-Analysen
- Export-Funktionen für Berichte

[![React](https://img.shields.io/badge/React-19+-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript)](https://typescriptlang.org)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

→ **[learn-smart.app/teacher](https://learn-smart.app/teacher)**

</td>
</tr>
</table>

---

## 🏗️ Systemarchitektur

```
┌─────────────────────────────────────────────────────────────────┐
│                        SLAM Ecosystem                           │
├──────────────────┬──────────────────┬───────────────────────────┤
│   📱 slam-app    │  👩‍🏫 slam-teacher  │      📚 slam-docs         │
│  Flutter App     │   React Dashboard │    MkDocs Dokumentation   │
│  iOS/Android/Web │   Vite/TypeScript │    GitHub Pages           │
└────────┬─────────┴────────┬─────────┴───────────────────────────┘
         │                  │
         ▼                  ▼
┌─────────────────────────────────────────────────────────────────┐
│                    ⚡ slam-backend                               │
│             Cloudflare Workers (Edge API)                       │
│                    Hono Framework                               │
├──────────────────┬──────────────────┬───────────────────────────┤
│  🔥 Firebase     │  🤖 Claude AI    │     🧠 Gemini AI           │
│  Auth + Firestore│  Sonnet 4.6      │     Pro 3 / Flash 3        │
│  (User Data)     │  Haiku 4.5       │     (Visualisierungen)     │
└──────────────────┴──────────────────┴───────────────────────────┘
```

---

## 🤖 KI-Modelle

| Aufgabe | Modell | Beschreibung |
|---------|--------|--------------|
| Fragen generieren | Claude Sonnet 4.6 | Adaptive, curriculumskonforme Aufgaben |
| Antworten bewerten | Claude Haiku 4.5 | Schnelle, präzise Auswertung mit Feedback |
| Personalisierte Hinweise | Claude Sonnet 4.6 | Maßgeschneiderte Lernhilfen |
| GeoGebra-Visualisierungen | Gemini Pro 3 | Dynamische mathematische Grafiken |
| KI-Labor Mini-Apps | Gemini Flash 3 | Interaktive Lernmodule on-the-fly |
| Bild-Analyse | Claude / Gemini | Handschrift & Aufgaben-Scan |

---

## 🎮 Gamification-System

```
📈 XP          →  Level aufsteigen & Ranglisten
🪙 Coins       →  Shop: Themes, Streak-Freezes, Power-Ups
🔥 Streak      →  Tägliches Lernen belohnen
🏆 Abzeichen   →  Meilensteine & besondere Leistungen
```

---

## 🛠️ Tech-Stack auf einen Blick

| Schicht | Technologie |
|---------|-------------|
| **Mobile/Web App** | Flutter 3.27+, Dart 3.6+, Riverpod 2.6+, Freezed, GoRouter |
| **Backend/API** | Cloudflare Workers, Hono, TypeScript 5+ |
| **Datenbank** | Google Firestore, Hive (lokal), Cloudflare KV |
| **Auth** | Firebase Authentication (Domain-restricted: `@mvl-gym.de`) |
| **KI** | Anthropic Claude (Sonnet 4.6, Haiku 4.5), Google Gemini (Pro 3, Flash 3) |
| **Docs** | MkDocs, GitHub Pages |
| **Lehrer-Dashboard** | React 19, Vite, TypeScript, Tailwind CSS |
| **CI/CD** | GitHub Actions (Build, Test, Deploy) |
| **Design** | Material 3, Google Sans Flex |

---

## 👥 Team

Entwickelt von Schülerinnen und Schülern des MVL-Gymnasiums im Rahmen des **Seminarkurs: Lernapp Mathematik**.

---

## 🌐 Live-Links

| Dienst | URL | Status |
|--------|-----|--------|
| 📱 Schüler-App | [app.learn-smart.app](https://app.learn-smart.app) | ![](https://img.shields.io/website?url=https%3A%2F%2Fapp.learn-smart.app&style=flat-square) |
| 🌍 Website | [learn-smart.app](https://learn-smart.app) | ![](https://img.shields.io/website?url=https%3A%2F%2Flearn-smart.app&style=flat-square) |
| ⚡ API | [api.learn-smart.app](https://api.learn-smart.app) | ![](https://img.shields.io/website?url=https%3A%2F%2Fapi.learn-smart.app&style=flat-square) |
| 📚 Docs | [docs.learn-smart.app](https://docs.learn-smart.app) | ![](https://img.shields.io/website?url=https%3A%2F%2Fdocs.learn-smart.app&style=flat-square) |

---

<div align="center">

</div>
