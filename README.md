# Inferno - GPT-OSS 20B Inference Engine

A Metal-accelerated inference engine for GPT-OSS 20B running on Apple Silicon.

Download the model weights from Hugging Face:

```bash
HF_TOKEN=$HF_TOKEN huggingface-cli download openai/gpt-oss-20b --include "original/*" --local-dir gpt-oss-20b/
```
