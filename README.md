# marimo-initial-learning

This repository is a minimal starting point for learning and experimenting with **Marimo**, a reactive Python notebook environment.

Marimo notebooks are stored as plain `.py` files, making them easy to version with Git, execute as scripts, or run as interactive apps. The focus here is on understanding Marimo’s execution model, reactivity, and basic UI elements through small, focused exercises.

## Tooling

This project uses **uv** to manage the Python environment and dependencies.

`uv` provides fast, reproducible project setup and handles virtual environments automatically, keeping the repository simple while avoiding manual venv management. This aligns well with Marimo’s emphasis on reproducibility and modern Python workflows.

## Scope

- Learning-first exercises
- Small, incremental notebooks
- Clear separation between experimentation and future production work

This repository is intentionally kept lightweight and will serve as a base for more advanced Marimo-based projects.
----------------------------------------------------
## Change Log (Human-Friendly Index)

See `CHANGELOG_INDEX.yaml` for a human-friendly index of changes.  
Each entry maps to an executable Marimo notebook and (optionally) an ADR:

- **Email PII classification update (2026‑02‑01)**  
  Key: `email-pii-classification-update-2026-02-01`  
  Notebook: `notebooks/CHANGELOG_2026-02-01.py`  
  ADR: `docs/decisions/0003-classification-policy.md`

- **Retention exception for HR datasets (2026‑02‑10)**  
  Key: `hr-retention-exception-2026-02-10`  
  Notebook: `notebooks/CHANGELOG_2026-02-10.py`