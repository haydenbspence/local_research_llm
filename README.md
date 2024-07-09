# Local Research LLM

NOTE: In Progress, 

Research often involves protected data. This repository aims to provide a robust framework for researchers who are interested in using local open-source language models (LLMs) on protected or sensitive datasets.

## Hardware

<details>
  <summary>Build 1 (240gb VRAM)</summary>

  #### Build 1 (240gb VRAM)

Type|Item|Price
:----|:----|:----
**CPU** | [Intel Xeon w5-3435X Hexadeca-core (16 Core) 3.10 GHz Processor ](https://www.intel.com/content/www/us/en/products/sku/233421/intel-xeon-w53435x-processor-45m-cache-3-10-ghz/specifications.html) | $1599.00
**Motherboard** | [ASUS Pro WS W790 SAGE SE Intel LGA 4677 CEB](https://www.asus.com/us/motherboards-components/motherboards/workstation/pro-ws-w790e-sage-se/) | $1,255
**Graphics Cards** | [ASUS Pro WS W790 SAGE SE Intel LGA 4677 CEB](https://www.asus.com/us/motherboards-components/motherboards/workstation/pro-ws-w790e-sage-se/) | $469.96 x 10
**Expansion Card** | [16x to 8X 8X Bifurcators](https://www.amazon.com/gp/product/B0BHNPKCL5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1) | $54.98
**Risers** | [Left-handed 90 degree risers (mobo to bifurcators)](https://www.amazon.com/LINKUP-PCIe-4-0-Riser-Cable/dp/B08XN21819?th=1) | $50 x  5
**Risers** | [Right-handed 90 degree risers (bifurcator to second GPU)](https://pcpartpicker.com/product/placeholder) | $50 x 10
**Case** | [Open Air Mining Rig Frame](https://a.co/d/0gD0LLP7) | $40

</details>


#### Build 2 ()


## Open-Source Models for Research

## Embedding Models

Text embeddings transform unstructured text data into a structured numerical format, enabling the comparison of different text elements, from single words to entire documents. These numerical representations allow for extensive processing and insight extraction. This technology powers numerous real-world applications, such as search engines, product recommendations, and content moderation.

The [Massive Text Embedding Benchmark (MTEB) Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) maintains a current ranking of embedding models that can be used locally. 

## Tips & Tricks

### Power Limiting

```{bash}
nvidia-smi --power-limit 185
```
