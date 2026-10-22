# Óscar Domínguez Álvarez

Final-year Computer Engineering student at Universidad de Salamanca, heading towards health data and clinical software.

## What I work on

The part I enjoy most is design: working out how a system should be structured before committing to it, and asking what a decision will cost in three years rather than whether it runs today. My ground is data modelling, relational design and access control, mostly in Python, SQL, C/C++, C# and Java.

## Recent work

**Clinical data system — IBSAL & Hospital Universitario de Salamanca** · Jul–Sep 2026

Sole developer on a data system for a haematopoietic stem cell transplant unit. The unit reports every transplant to the European EBMT registry across 29 official forms, and needs the same data again for patient care and statistics, so it was being captured twice. I designed a system where each data point is captured once and serves both: a data dictionary as the single source of truth with traceability back to the source form, around 70 tables built on a generalised clinical-event structure, and access control down to record level per centre. Handed over with 39 documented design decisions and the alternatives I rejected.

Not public — it runs inside a hospital.

## Currently

**Final-year project** — a proactive AI companion for older adults living alone or with early cognitive decline. Local-first, privacy by design, rule-driven rather than a black box. Repository coming.

**Learning HL7 FHIR** — the interoperability standard European healthcare is converging on ahead of the European Health Data Space.

## Personal projects

- **[vitalpulse-api](https://github.com/oscar-dom/vitalpulse-api)** · TypeScript · 2026. HL7 FHIR R4 server for vital signs, with a React web app for clinicians. Patients and observations are FHIR resources with LOINC codes and UCUM units, and the server interprets every value against its reference range. Versioned resources with optimistic locking, paged search Bundles, every error returned as an OperationOutcome, admin and clinician roles, integration tests and OpenAPI docs.
- **[claude-config](https://github.com/oscar-dom/claude-config)** · Shell · 2026. My Claude Code setup, synced across devices with installers for Windows and macOS/Linux. Includes a skill that sets up Git Flow on a repository: protected branches, PR templates and CI.
- **[restaurant-manager-wpf](https://github.com/oscar-dom/restaurant-manager-wpf)** · C# / WPF · 2025. Desktop app for running a restaurant floor: table states, orders, tickets and hand-drawn consumption charts.
- **[task-manager-notion](https://github.com/oscar-dom/task-manager-notion)** · Java · 2024. Console task manager built on MVC, with interchangeable storage behind a single interface: a local file or a Notion database through its API.

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/oscar-dominguez-alvarez/)
