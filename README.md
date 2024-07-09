# Local Research LLM

NOTE: In Progress, please do not use!

Research often involves protected data. This repository aims to provide a robust framework for researchers who are interested in using local open-source language models (LLMs) on protected or sensitive datasets.

## Builds and Hardware

### Inference Only

- [Llama 400B Inference Server - 384GB - DDR5 RDIMM](./builds/01.md)

### Inference and Training

- [The Standard - 48GB - VRAM]()

## Open-Source Models for Research

## Embedding Models

Text embeddings transform unstructured text data into a structured numerical format, enabling the comparison of different text elements, from single words to entire documents. These numerical representations allow for extensive processing and insight extraction. This technology powers numerous real-world applications, such as search engines, product recommendations, and content moderation.

The [Massive Text Embedding Benchmark (MTEB) Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) maintains a current ranking of embedding models that can be used locally. 

## Tips & Tricks

### Power Limiting

```{bash}
nvidia-smi --power-limit 185
```
