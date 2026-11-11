<div align="center">

### Pico Moorhead

local AI infrastructure · your models, your machine

![DGX Spark](https://img.shields.io/badge/DGX_Spark-4_nodes-76b900?style=flat-square&labelColor=000000)
![RoCE](https://img.shields.io/badge/RoCE-200_GbE-76b900?style=flat-square&labelColor=000000)
![Context](https://img.shields.io/badge/context-1M-76b900?style=flat-square&labelColor=000000)
![Throughput](https://img.shields.io/badge/throughput-438_tok%2Fs-76b900?style=flat-square&labelColor=000000)

</div>

---

## Two things I've built

### [pico-dgx-ds4](https://github.com/Picom-code/pico-dgx-ds4)

DeepSeek-V4.1-Flash on four DGX Sparks, meshed over 200 GbE RoCE. Hand-written CUDA kernels,
a Rust OpenAI-compatible front-end, and a 1M-token context window on hardware that fits under a desk.

|  |  |
|---|---|
| aggregate | **441 tok/s** at 16 concurrent users |
| single stream | **143 tok/s** code · 89.5 chat |
| cold prefill | **~10k tok/s** |

### [ezlm](https://github.com/Picom-code/ezlm)

Your own model, running on your own computer. One click, no cloud, no API keys, no per-token bill.

**[picom-code.github.io/ezlm](https://picom-code.github.io/ezlm/)**

---

**Day job** — technical marketing engineer at NVIDIA: AI agents, MCP, NeMo Agent Toolkit, Brev.

`cuda` · `python` · `rust` · `typescript` · `pytorch`
