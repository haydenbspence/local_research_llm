# Local Research LLM

NOTE: In Progress, please do not use!

Research often involves protected data. This repository aims to provide a robust framework for researchers who are interested in using local open-source language models (LLMs) on protected or sensitive datasets.

## Hardware

Type|Item|Price
:----|:----|:----
**CPU** | []() | $10
**Motherboard** | []() | $10
**Graphics Cards** | []() | $10
**Expansion Card** | []() | $10
**Risers** | []() | $10
**Case** | []() | $10

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

<details>
  <summary>LLaMA 400B Inference Server</summary>
  This hypothetical build by the HuggingFace engineer [Matthew Carrigan](https://github.com/rocketknight1) is designed to inference the LLaMA 400B model.
  It has two variants, a single socket and dual socket. We outline the dual socket here.

  **NOTE:** This build has not been tested.

  T/s: 1-2

  #### Llama 400 Inference Server (384GB DDR5 RDIMM)
  [source](https://x.com/carrigmat/status/1804161634853663030)
  Type|Item|Price|Amount
  :----|:----|:----|:----
  **CPU(s)** | [AMD EPYC 9124](https://www.amd.com/en/products/processors/server/epyc/4th-generation-9004-and-8004-series/amd-epyc-9124.html) | $1300 | 2
  **Motherboard** | [Gigabyte MZ73-LM1](https://www.gigabyte.com/Enterprise/Server-Motherboard/MZ73-LM1-rev-1x) | $1800 | 1
  **RAM** | [4800mhz+ 16GB DDR5 RDIMM](https://store.supermicro.com/us_en/16gb-ddr5-4800-mem-dr516l-sl02-er48.html) | $130 | 24
  **Power Supply** | [Corsair HX1000i](https://www.corsair.com/us/en/p/psu/cp-9020259-na/hx1000i-fully-modular-ultra-low-noise-platinum-atx-1000-watt-pc-power-supply-cp-9020259-na) | $235 | 1
  **Enclosure** | [PHANTEKS Enthoo Pro 2 Server](https://www.phanteks.store/collections/enthoo-pro-2-server-edition/products/phanteks-enthoo-pro-2-server-edition-closed-side-panel-black) | $160 | 1
  **CPU Heatsink** | [COOLSERVER AMD SP5 4U-S42 6 Heat Pipes Server CPU Cooler Tower](https://www.aliexpress.us/item/3256804876452464.html?gatewayAdapt=glo2usa4itemAdapt) | $50 | 2
</details>


## Open-Source Models for Research

## Embedding Models

Text embeddings transform unstructured text data into a structured numerical format, enabling the comparison of different text elements, from single words to entire documents. These numerical representations allow for extensive processing and insight extraction. This technology powers numerous real-world applications, such as search engines, product recommendations, and content moderation.

The [Massive Text Embedding Benchmark (MTEB) Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) maintains a current ranking of embedding models that can be used locally. 

## Tips & Tricks

### Power Limiting

```{bash}
nvidia-smi --power-limit 185
```
