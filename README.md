<div align="center">

### Pico Moorhead

local AI infrastructure · your models, your machine

![DGX Spark](https://img.shields.io/badge/DGX_Spark-4_nodes-ffffff?style=flat-square&labelColor=000000)
![RoCE](https://img.shields.io/badge/RoCE-200_GbE-bbbbbb?style=flat-square&labelColor=000000)
![Context](https://img.shields.io/badge/context-1M-bbbbbb?style=flat-square&labelColor=000000)
![Throughput](https://img.shields.io/badge/16_users-376_tok%2Fs-bbbbbb?style=flat-square&labelColor=000000)

</div>

---

<a href="https://github.com/Picom-code/pico-dgx-ds4"><img src="https://raw.githubusercontent.com/Picom-code/pico-dgx-ds4/main/assets/banner.png" alt="pico-dgx-ds4: DeepSeek V4.1 Flash on 4x DGX Spark" width="100%"></a>

### [pico-dgx-ds4](https://github.com/Picom-code/pico-dgx-ds4)

DeepSeek V4.1 Flash on four DGX Sparks over a 200 GbE RoCE switch, built so many people can share one cluster.
A fork of [blaesus/dsgx10](https://github.com/blaesus/dsgx10): faster single-user, 2x+ the multi-user throughput,
1M context, 16 slots, image input.

```
  1 user ........ 90 chat / 144 code tok/s
  16 users ...... 376 tok/s, a different prompt each
  context ....... 1M
  prefill ....... 10k tok/s
```

<br>

<a href="https://github.com/Picom-code/ezlm"><img src="https://raw.githubusercontent.com/Picom-code/ezlm/main/.github/hero.png" alt="EZLM: your own AI, running on your computer" width="100%"></a>

### [ezlm](https://github.com/Picom-code/ezlm)

Your own model, running on your own computer. EZLM scans your machine, picks the smartest model it can run well,
and hands you a private URL and key. No account, no cloud, no command line.

**[Download for Windows](https://github.com/Picom-code/ezlm/releases/latest/download/EZLM-Setup.exe)** ·
**[Download for Mac](https://picom-code.github.io/ezlm/#download)** ·
[picom-code.github.io/ezlm](https://picom-code.github.io/ezlm/)

---

**Day job** — technical marketing engineer at NVIDIA: AI agents, MCP, NeMo Agent Toolkit, Brev.

`cuda` · `python` · `rust` · `typescript` · `pytorch`
