---
title: career_conversation
app_file: main.py
sdk: gradio
sdk_version: 6.12.0
---
# Agent CV: My own agentic professional version of me

Taken from Agents course lab [here](https://github.com/ed-donner/agents/blob/main/1_foundations/4_lab4.ipynb).

## Live Version

This has been deployed to Huggingface Spaces [here](https://huggingface.co/spaces/reanblock/career_conversation).

## Deploy

Run the following code to deploy this to a Hugging Face Space:

```bash
uv tool install 'huggingface_hub[cli]
hf auth login --token YOUR_TOKEN_HERE
hf auth whoami
```

## Install & Run

Run the following code to run this locally.

```bash
uv run main.py
```