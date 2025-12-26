# OctoFit Tracker (skeleton)

Minimal scaffold for the OctoFit Tracker app.

Project structure

```
octofit-tracker/
├── backend/
│   ├── venv/  # python virtualenv (ignored)
│   ├── octofit_tracker/  # Django app / project (sample settings here)
│   └── requirements.txt
└── frontend/
```

Quick start

1. Create and activate the virtualenv (already created in this workspace):

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
pip install -r octofit-tracker/backend/requirements.txt
```

2. A minimal sample Django settings file is provided at `octofit-tracker/backend/octofit_tracker/settings.py`.

Notes
- Replace the `SECRET_KEY` in production.
- The sample settings use SQLite by default; a commented example shows how to configure `djongo`/MongoDB.
