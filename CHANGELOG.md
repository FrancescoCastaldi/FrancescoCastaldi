# Changelog: Francesco Castaldi GitHub Special Repository

Tutte le modifiche rilevanti a questo progetto sono documentate in questo file.
Il formato e basato su [Keep a Changelog](https://keepachangelog.com/it/1.1.0/) e aderisce a [Semantic Versioning](https://semver.org/lang/it/).

---

## [Unreleased]

## [1.0.3] - 2026-10-20

### Added
- Inclusione di quattro nuovi upstream nella tabella Open Source con relativi trafiletti narrativi: `walkersutton/Cyclemetry` (5 merged: hardening del render-core, telemetria calorie con summary su attivita e UI, overlay trim brackets sulla timeline di playback, fix Svelte 5 runes con caption di accessibilita video), `iausathub/satchecker` (5 in review: conversione ECEF/ITRS, limite superiore per date oltre due settimane nel futuro, conteggi objects e satellites processed nelle metriche FOV, rimozione del parametro duplicato execution_time, documentazione della regola newest-before per TLE at epoch), `netdata/netdata` (`#24352` in review: space charting saltato per drive ottiche e read-only su Windows) e `PostHog/posthog.com` (`#21289` in review: gestione degli errori API e cleanup del loading state in `useTeam`).

### Changed
- Sincronizzazione live delle Pull Request Open Source al 20 Ottobre 2026: Mattermost passa a `1 merged · 3 in review` dopo il merge della PR `#550` (spaziatura AM/PM negli eventi calendario, Issue #318).
- Aggiornamento delle annotazioni di review delle PR Superset: `#45038`, `#45039` e `#45051` approvate con CI verde; `#44945` e `#44358` approvate; `#43695` approvata con check CI non verdi.

### Removed
- Rimozione dei cinque repository privati dalla tabella Selected Work (`sql-performance-copilot`, `yaris-hv-fan-optimizer`, `hailcast-ml`, `portfolio-tracker`, `CheckLensRB`) per eliminare i link 404 verso i visitatori pubblici del profilo.

## [1.0.2] - 2026-10-13

### Added
- Inclusione del progetto pubblico `BenzaTracker` nella sezione Selected Work con stack tecnologico (`Python, Flask, SQLite`).
- Aggiunta della nuova PR upstream attiva `#45205` su Apache Superset (copertura unit test per i database engine spec CockroachDB, MotherDuck, DynamoDB, Firebolt, Google Sheets, Synapse e OceanBase).

### Changed
- Sincronizzazione live delle Pull Request Open Source al 13 Ottobre 2026: Apache Superset passa a `12 merged · 9 in review` con il merge delle PR `#45036` e `#44355` e l'approvazione con CI verde di `#44945`.
- Aggiornamento della voce Stratum Suite con specifica della compatibilita Apache Superset 6.1.0 e versione `v0.3.3` per `hierarchical-table`.

---

## [1.0.1] - 2026-10-11

### Added
- Restyling geometrico e bilanciamento simmetrico della sezione Activity con layout a due colonne (437px ciascuna, 874px complessivi): card metriche GitHub e contribution streak perfettamente allineate sotto il banner da 880px.
- Bordature hairline sottili (token `#3A372F` dark e `#D2C9B6` light con border-radius a 8px) coerenti con i divisori hairline bespoke del profilo.
- Sincronizzazione narrativa Trino con PR upstream attiva #31546 (Iceberg NDV retention).
- Token formali `card_width`, `card_height`, `border_color`, `border_radius` registrati in `design_tokens.json` e specchiati nella configurazione globale Gemini.

### Changed
- Eliminata la card orfana asimmetrica dei linguaggi dalla sezione Activity e rimosso l'overflow orizzontale che provocava il wrapping su schermi standard.
- Risolto definitivamente il disservizio del vecchio endpoint `github-readme-activity-graph` (HTTP 402).
- Aggiornamento stato PR Open Source al 11 Ottobre 2026.

---

## [1.0.0] - 2026-10-11

### Added
- Release iniziale e consolidamento del repository nello spazio di lavoro unificato.
