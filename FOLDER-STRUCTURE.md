# Folder structure

Where files live in this repo and why. Update this file whenever the structure changes.

- `data/` - source datasets and prompts fed into eval runs
- `runs/` - raw outputs from eval runs, one folder or file per run
- `labels/` - human or model labels applied to run outputs
- `analysis/` - scripts and notebooks that turn labelled runs into findings
- `docs/` - project documentation and write-ups

Root files:

- `README.md` - what the project is
- `.gitignore` - keeps secrets (.env, *.key), sealed mappings, Python caches, and local session state out of git
