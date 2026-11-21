# First App course starter

**Draft starter template** for the First App course. It prepares a Python workspace in GitHub Codespaces; it is not a finished app. Start from this template to create your own repository, then open it in Codespaces.

## Ask your coding agent to explain the files

When your Codespace is ready, open Codex or the Claude extension and ask:

> I’m learning to build my first app. Explain only the tracked starter files `README.md`, `requirements.txt`, `.gitignore`, and `.devcontainer/devcontainer.json` in beginner-friendly language. Do not read secrets, credentials, environment files, or untracked files. Do not change or run anything.

You can ask follow-up questions before asking the agent to make changes. Agent availability and behavior depend on your account, setup, and current product support; this template does not install or configure an agent for you.

## What is included

- `.devcontainer/devcontainer.json` selects a Python 3.12 Codespaces environment, installs listed dependencies when the container is created, and forwards port 8501. Check that the port is marked **Private** in the Codespace Ports tab before opening the preview.
- `requirements.txt` lists Streamlit, a framework for building simple interactive Python apps, and Requests, a library for making HTTP requests.
- `.gitignore` keeps common Python caches and local secret files out of Git.

## Run your app

There is no app code in this starter. After creating an app file such as `app.py`, run it in the Codespaces terminal:

```bash
python -m streamlit run app.py
```

Codespaces should offer port 8501 when Streamlit starts. Check that its visibility is **Private** before opening or sharing the preview. Keep secrets out of source control; `.gitignore` helps, but does not prevent an agent from reading files or replace careful handling. Follow the course instructions for creating and running your app.

This starter does not guarantee eligibility or access to GitHub Codespaces, Codex, or the Claude extension. Check current provider requirements and age eligibility before creating accounts or using these services.
