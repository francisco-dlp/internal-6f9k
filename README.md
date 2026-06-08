# JEElS 2026 Workshop — Instructor Materials

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/francisco-dlp/internal-6f9k/HEAD)

Instructor version of the exspy workshop materials for JEElS 2026.

This repository contains both the **unfilled (student)** and **filled (solution)**
notebooks for the workshop, plus all supporting datasets and Binder configuration.
Two formats are available: standard Jupyter notebooks (`.ipynb`) and
[Marimo](https://marimo.io/) notebooks (`.py`).

## Contents

| Notebook | Description |
|---|---|
| `1 - Getting Started/01_Getting_Started.*` | Introduction to HyperSpy signals, loading, axes, indexing, and ROIs |
| `2 - EELS/EELS_elemental_mapping.*` | Elemental mapping of Cu/Zn nanoparticles from EELS data |
| `2 - EELS/EELS_finestructure_analysis.*` | EELS fine structure analysis of LaSrMnO₃ thin films |
| `binder/requirements.txt` | Pinned dependencies for the Binder environment |

Unfilled versions (with TODO placeholders) are in the public repository. Filled
versions with complete solutions are available here in the instructors' repository.

## Launch on Binder

Click the badge above to launch this environment. The Binder image is the same as
the participant image — only the notebooks differ.

## Running with Marimo

The same notebooks are also available as [Marimo](https://marimo.io/) `.py` files
alongside each `.ipynb`. To run them:

```bash
pip install marimo>=0.23.8
marimo edit "notebooks/1 - Getting Started/01_Getting_Started_unfilled.py"
```

Marimo notebooks are reactive — cells automatically re-run when their inputs
change, and the UI provides a clean, app-like experience.

You can also run them in read-only mode without the editor:

```bash
marimo run "notebooks/1 - Getting Started/01_Getting_Started_unfilled.py"
```

For a full list of Marimo features, see the [Marimo documentation](https://docs.marimo.io/).

## Participant Repo

Participants should use the public workshop repo instead:

[github.com/francisco-dlp/jeels2026_workshop](https://github.com/francisco-dlp/jeels2026_workshop)

## Local Setup

If you prefer to run locally:

```bash
python -m venv venv
source venv/bin/activate
pip install -r binder/requirements.txt
jupyter lab
```
