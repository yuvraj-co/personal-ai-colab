# Personal AI on Google Colab

A small, intentionally simple Colab notebook for running **Qwen3-4B-Instruct-2507** in 4-bit mode on an allocated GPU and launching a password-protected Gradio chat UI.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yuvraj-co/personal-ai-colab/blob/main/Personal_AI_Colab.ipynb)

## Run it

1. Open `Personal_AI_Colab.ipynb` in Colab (choose **Runtime → Change runtime type → T4 GPU** or another available GPU).
2. Run the notebook from top to bottom.
3. Enter a unique username/password in the final cell and open the printed Gradio link.

The first launch downloads the model weights. Colab runtimes are temporary and GPU access is subject to availability and limits. The web link is internet-accessible and password-protected; do not share the link or password and do not enter sensitive information.

## Model and license

- Model: [`Qwen/Qwen3-4B-Instruct-2507`](https://huggingface.co/Qwen/Qwen3-4B-Instruct-2507)
- Model license: Apache 2.0 (review the model card and license for details)
- Frameworks: Transformers, bitsandbytes, Gradio
- This repository contains notebook code, not the model weights.

## Limits

The initial version is a chatbot, not a fully autonomous agent. It has no live web-search tool, no shell, no Google-account access, and no unrestricted file access. Colab sessions stop/disconnect and the temporary Gradio link is not a permanent hosting solution.
