# MLLM_Factory

Multi-modal model training are very sensitive to their training strategy and settings, to make full use of opensource facility works such as LLaVA, QwenVL etc, I orgainized some SOTA multi modal LLM implementation here. It able to pretrain and finetune many kinds of Vision Encoders & LLMs as well as different vision-llm adaptors.
Current supported model arch design is:

- LLaVA 1.5;
- LLaVA 1.6;
- Qwen VL;
- MiniGemini;
- Flamingo;
- MiniCPM;
- Vary;

For large language models, here are supported one:

- Qwen1.5 series;
- Llama3 series;

The bridge between LLM and Vision encoders, we supported many different implementations:

- LLaVA like MLP adaptors;
- QwenVL like Resampler;
- Perceiver Resampler;
- Complicated Perceiver Resamper;

Be noted that, these combinations between different Vision Encoder && Adaptors are quite sensetive, you could be easily diconvergence at anytime if you aren't have a full experiences in MLLM training. But don't warry, that's the reason why we are here.

The utlimate goal of this repo is:

> Makeing MLLM pretraining && finetune can be easily reimplemented, democrization MLLM training to anyone!


## Quick Start

The whole project architecture are merely same as LLaVA, to the best of understanding the project, we choose kept it as simple as possible, we didn't event change the package name in case anyone PR their forks from original LLaVA repo!

You can follow original LLaVA installation guide to setup **MLLM_Factory**.


## Status

Currently the code are on the edge of release, please star and watch for the quickist updates!

