# MLLM_Factory

Multi-modal model training is very sensitive to its training strategy and settings. To make full use of open-source frameworks such as LLaVA, QwenVL, etc., I have organized some state-of-the-art multi-modal LLM implementations here. This repository is able to pretrain and fine-tune various types of Vision Encoders & LLMs, as well as different vision-LLM adaptors.
The currently supported model architectures are:

- LLaVA 1.5
- LLaVA 1.6
- Qwen VL
- MiniGemini
- Flamingo
- MiniCPM
- Vary

For large language models, the following ones are supported:

- Qwen1.5 series
- Llama3 series

To bridge the gap between LLM and Vision encoders, we have supported various implementations:

- LLaVA-like MLP adaptors
- QwenVL-like Resampler
- Perceiver Resampler
- Complicated Perceiver Resampler

Please note that the combinations between different Vision Encoders and Adaptors are quite sensitive. You may easily encounter divergence if you don't have sufficient experience in MLLM training. But don't worry, that's why we are here to help.
The ultimate goal of this repository is:

> To make MLLM pretraining and fine-tuning easily re-implementable, democratizing MLLM training for everyone!

## Quick Start

The overall project architecture is almost the same as LLaVA. To better understand the project, we have kept it as simple as possible. We haven't even changed the package name in case anyone wants to contribute their forks from the original LLaVA repository!
You can follow the original LLaVA installation guide to set up MLLM_Factory.

## Status
Currently, the code is on the verge of release. Please star and watch for the quickest updates!
