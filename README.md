---
title: career_conversation
app_file: main.py
sdk: gradio
sdk_version: 6.12.0
---
# Agent CV: My own agentic professional version of me


## Live Version

This has been deployed to Huggingface Spaces [here](https://huggingface.co/spaces/reanblock/career_conversation).

## Deploy

```bash
uv tool install 'huggingface_hub[cli]
hf auth login --token YOUR_TOKEN_HERE
hf auth whoami
```

## Install & Run

```bash
uv run main.py
```