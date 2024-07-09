# Local Research LLM

Research often involves protected data. This repository aims to provide a robust framework for researchers who are interested in using local open-source language models (LLMs) on protected or sensitive datasets.

## Hardware

Type|Item|Price
:----|:----|:----
**CPU** | [Intel Xeon w5-3435X](https://pcpartpicker.com/product/placeholder) | -
**Motherboard** | [ASUS Pro WS W790 SAGE SE Intel LGA 4677 CEB](https://pcpartpicker.com/product/placeholder) | -
**Expansion Card** | [16x to 8X 8X Bifurcators]([https://pcpartpicker.com/product/placeholder](https://www.amazon.com/gp/product/B0BHNPKCL5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1)) | $54.98
**Risers** | [Left-handed 90 degree risers (mobo to bifurcators)](https://pcpartpicker.com/product/placeholder) | -
**Risers** | [Right-handed 90 degree risers (bifurcator to second GPU)](https://pcpartpicker.com/product/placeholder) | -

## Open-Source Models for Research

## Embedding Models

Text embeddings transform unstructured text data into a structured numerical format, enabling the comparison of different text elements, from single words to entire documents. These numerical representations allow for extensive processing and insight extraction. This technology powers numerous real-world applications, such as search engines, product recommendations, and content moderation.

The [Massive Text Embedding Benchmark (MTEB) Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) maintains a current ranking of embedding models that can be used locally. 

## Tips & Tricks

### Power Limiting

```{bash}
nvidia-smi --power-limit 185
```
