# Sahan Thanthiriwatte

Chemist by training, sysadmin by trade, LIMS analyst by day. I build small,
single-binary desktop tools that get analytical-instrument results into a
laboratory information management system — with the analyst reviewing every
result before anything posts.

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri_2-24C8D8?logo=tauri&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

---

## What I work on

Lab systems for the QC laboratories at **The Coca-Cola Company**, where I've
been the SampleManager LIMS analyst since 2018.

- **Instrument-to-LIMS desktop apps.** Rust + Tauri, ~6 MB single `.exe`,
  no server, no installer, no per-PC drivers. Each one reads sample context
  from the LIMS (read-only), applies the method's calculation and QC rules
  in tested code, shows the analyst every result against its specification,
  and writes the results file the LIMS already knows how to ingest.
- **Retiring Excel/VBA and InfoPath workflows** — the output of each new app
  is locked byte-for-byte against the workbook it replaces, so nothing
  downstream changes.
- **SampleManager LIMS administration** — configuration, master data,
  reporting, integrations, and change control in a GMP/GLP setting. Led the
  11.1 → 12.1 SP2 and 12.1 → 12.3 upgrades.
- **AI-assisted development** — most of the above is built with Claude Code
  in a spec → plan → test → review loop, one branch and worktree per topic.

## In the open

| | |
|---|---|
| [**AP_Chem_Prep**](https://github.com/SahanGH/AP_Chem_Prep) | A full-year AP® Chemistry course pack in LaTeX — guided notes, worksheets, unit exams, review sheets — aligned to the 2024 CED. Every document builds to four variants (student / key × print / screen) from one source. |
| [**Automate-Invoice-Data-Entry**](https://github.com/SahanGH/Automate-Invoice-Data-Entry) | Invoice data extraction with VBA and an AI vision model. |

## Background

- PhD in chemistry; postdoc at Georgia Tech (computational chemistry on
  HPC clusters), then research scientist and HPC administrator at the
  University of Alabama — 26 peer-reviewed publications along the way.
- Systems administrator at the Federal Reserve Bank of Atlanta
  (Windows/AD, Linux HPC, macOS).
- Red Hat Certified Engineer · AWS Certified Solutions Architect.

## Toolbox

**Building:** Rust · Tauri 2 · React · TypeScript · Tailwind · Vite
**Data:** SQL Server · SQLite · SampleManager LIMS
**Scripting & docs:** PowerShell · Python · VBA · LaTeX
**Platforms:** Windows · Linux · macOS

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/sahanchem) · Atlanta, GA
