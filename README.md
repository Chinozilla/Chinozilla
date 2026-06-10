# Anhthien Nguyen

Wirtschaftsinformatik-Student (B.Sc., Technische Hochschule Mittelhessen) und Gründer von
[kartenmesse.de](https://www.kartenmesse.de) — dem deutschsprachigen Live-Aggregator für
Trading-Card-Game-Events.

## Was ich baue

### [kartenmesse.de](https://www.kartenmesse.de) — Full-Stack-Produkt in Produktion

Solo entwickelt und betrieben, von der Idee bis zum laufenden Geschäft: Event-Datenbank mit
Moderations-Workflow, interaktive Karte (MapLibre GL), TCG-News-Redaktion, programmatische
SEO-Landingpages, E-Mail-Benachrichtigungen mit Double-Opt-in und Monetarisierung über
Google AdSense und Amazon-Affiliate.

**Stack:** Next.js 15 (App Router) · TypeScript · Supabase (PostgreSQL, RLS) · Tailwind CSS · Vercel

Der Quellcode ist privat (kommerzielles Produkt). Architektur, Technik-Entscheidungen und
Screenshots sind öffentlich dokumentiert:
**→ [kartenmesse-showcase](https://github.com/Chinozilla/kartenmesse-showcase)**

### [council-kit](https://github.com/Chinozilla/council-kit) — Multi-Agenten-Framework (Claude Agent SDK)

Für kartenmesse.de betreibe ich eine autonome KI-„Redaktion": spezialisierte Agenten für
Content, News, Web-Research, Legal-Prüfung und QA — mit Reviewer-Veto-Hierarchie als
Qualitätsmauer, Lease-basierter Parallelitätskontrolle und zentraler Problem-Datei statt
direkter Nutzer-Kommunikation. **council-kit** ist der generische Open-Source-Kern dieses
Produktionssystems: Maker-Checker-Review-Loops, Worker-Leases, deduplizierte Problem-Sinks.

### [ssrf-safe-fetch](https://github.com/Chinozilla/ssrf-safe-fetch) — SSRF-Schutz für Node.js

Dependency-freie Security-Bibliothek, extrahiert aus dem kartenmesse-Backend:
Private-IP-Blocking (IPv4 + IPv6), DNS-Validierung, Re-Validierung jedes Redirect-Hops.
127 Unit-Tests.

### [tcg-price-pipeline](https://github.com/Chinozilla/tcg-price-pipeline) — Daten-Pipeline (Python)

Inkrementelle ETL-Pipeline für Magic-Kartenpreise (Scryfall-API): pandas-Transformationen,
SQLAlchemy-Snapshots (SQLite/PostgreSQL), Streamlit-Dashboard mit Preis-Trends und
Top-Movers — entstanden aus meinem eigenen TCG-Handel.

## Tech

TypeScript · Next.js / React · PostgreSQL / Supabase · Python ·
Claude Agent SDK / Anthropic API · Tailwind CSS · Vercel · Git / GitHub Actions

## Kontakt

anhthiennguyen99@gmail.com · [kartenmesse.de](https://www.kartenmesse.de)
