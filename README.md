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

## Running with molab (cloud-hosted marimo)

The same notebooks are also available as [Marimo](https://marimo.io/) `.py` files.
You can run them directly in your browser on [molab](https://molab.marimo.io/),
a free cloud-hosted marimo notebook service — no local installation required.

**Public repository (unfilled notebooks):**

| Notebook | Open in molab |
|---|---|
| Getting Started | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/jeels2026_workshop/blob/main/notebooks/1%20-%20Getting%20Started/01_Getting_Started_unfilled.py) |
| EELS Elemental Mapping | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/jeels2026_workshop/blob/main/notebooks/2%20-%20EELS/EELS_elemental_mapping.py) |
| EELS Fine Structure | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/jeels2026_workshop/blob/main/notebooks/2%20-%20EELS/EELS_finestructure_analysis.py) |

**Instructor repository (filled notebooks):**

| Notebook | Open in molab |
|---|---|
| Getting Started | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/internal-6f9k/blob/main/notebooks/1%20-%20Getting%20Started/01_Getting_Started_completed.py) |
| EELS Elemental Mapping | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/internal-6f9k/blob/main/notebooks/2%20-%20EELS/EELS_elemental_mapping_full.py) |
| EELS Fine Structure | [![Open in molab](https://marimo.io/molab-shield.svg)](https://molab.marimo.io/github/francisco-dlp/internal-6f9k/blob/main/notebooks/2%20-%20EELS/EELS_finestructure_analysis_full.py) |

Marimo notebooks are reactive — cells automatically re-run when their inputs
change, and the UI provides a clean, app-like experience.

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
