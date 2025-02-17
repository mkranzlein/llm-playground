# llm-playground
Tinkering and experimenting with LLM APIs and related platforms and tools

## Setup

```shell
pyenv virtualenv 3.13.2 llm-playground
```

```shell
pyenv activate llm-playground
```

```shell
pip install -r requirements.txt
```

## TODO: add pyproject.toml with install

# Useful libraries
- [bitsandbytes](https://huggingface.co/docs/bitsandbytes/main/en/index): "Enables accessible large language models via k-bit quantization for PyTorch"
- [trl](https://huggingface.co/docs/trl/index): "A set of tools to train transformer language models with Reinforcement Learning"
    - Transformer Reinforcement Learning
- [OpenRLHF](https://github.com/OpenRLHF/OpenRLHF): "A high-performance RLHF framework built on Ray, DeepSpeed and HF Transformers"
- [vLLM](https://github.com/vllm-project/vllm): "Easy, fast, and cheap LLM serving for everyone"
    - "v" for "virtual" originally, but also "velocity" and "victory"
- [ray](https://github.com/ray-project/ray): "Unified framework for scaling AI and Python applications"