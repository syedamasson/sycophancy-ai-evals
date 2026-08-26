# Folder structure

Where files live in this repo and why. Update this file whenever the structure changes.

- `data/` - source datasets and prompts fed into eval runs
- `runs/` - raw outputs from eval runs, one folder or file per run
- `labels/` - human or model labels applied to run outputs
- `analysis/` - pipeline scripts (blind-set builder, judge, results) and notebooks. Run them from the repo root so relative paths to runs/ and labels/ resolve
- `docs/` - project documentation and write-ups

Root files:

- `README.md` - what the project is, the results, and a file-by-file map
- `runner.py` - the entry point: sends the 48 calls and writes the raw run file. Lives at the root because every run command starts with `python runner.py`
- `.env.example` - the environment variable names the scripts need, with placeholder values. Copy to `.env` and fill in
- `.gitignore` - keeps secrets (.env, *.key), sealed mappings, Python caches, and local session state out of git
