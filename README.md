# Private AI Home Server

**Local AI hardware** offers a compelling alternative to cloud-based solutions for running LLMs.
By leveraging local edge computing, users can **process and store their data on-site,
ensuring that sensitive information remains secure and out of reach from third-party surveillance or data breaches.**

## What you will find here

An overview of different **hardware, reviews and resources** I put together while figuring out what to buy.\
All with a focus on high quality and getting the best price-to-performance ratio.

Maybe it will help you too - if you like it, give it a thumbs up!\
Also, make sure to support the sources - they did a great job!

## Hardware

| Name                                         | Processor                               | Memory | Bandwidth | PCIe (v/l/m)   | Ethernet  | Fan Noise (idle/load) |
| -------------------------------------------- | --------------------------------------- | ------ | --------- | -------------- | --------- | --------------------- |
| Apple                                        |                                         |        |           |                |           |                       |
| _[Apple Mac Mini][apple-mini-m5-pro]_        | [M5 Pro][apple-mini-m5-pro]             | ?      | ~348GB/s  | -              | 10G       | 0db / ?               |
| [Apple Mac Studio][apple-studio-m4-max]      | [M4 Max][apple-studio-m4-max]           | ≤128GB | 546GB/s   | -              | 10G       | 0db / 44db            |
| AMD                                          |                                         |        |           |                |           |                       |
| _[Beelink AI Mini][beelink-ai-mini]_         | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | ?              | ?         | ?                     |
| [Beelink GTR9 Pro][beelink-gtr9-pro]         | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | -              | 10G (2x)  | ?                     |
| [Corsair AI Workstation 300][corsair-ai-300] | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | ?              | 2.5G      | ?                     |
| [Framework Desktop][framework-desktop]       | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | 4.0 / x4 / x4  | 5G        | 0dB / 48dB            |
| [GMKtec EVO-X2][gmktec-evo-x2]               | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | -              | 2.5G      | 27dB / 55dB           |
| [HP Z2 Mini G1a Workstation][hp-z2-mini]     | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | -              | 2.5G      | 32dB / 67dB           |
| [Minisforum MS-S1 Max][minisforum-s1max]     | [AMD Ryzen AI Max+ 395][amd-strix-halo] | ≤128GB | 256GB/s   | 4.0 / x4 / x16 | 10G (2x)  | ?                     |
| NVIDIA                                       |                                         |        |           |                |           |                       |
| [Dell Pro Max][dell-pro-max]                 | [NVidia GB10][nvidia-grace-blackwell]   | ≤128GB | 273GB/s   | -              | 200G (2x) | ?                     |
| [NVIDIA DGX Spark][nvidia-dgx-spark]         | [NVidia GB10][nvidia-grace-blackwell]   | ≤128GB | 273GB/s   | -              | 200G (2x) | ?                     |

<!-- npus -->

[amd-strix-halo]: https://www.amd.com/en/products/processors/laptop/ryzen/ai-300-series/amd-ryzen-ai-max-plus-395.html
[apple-studio-m4-max]: https://www.apple.com/shop/buy-mac/mac-studio/apple-m4-max-with-14-core-cpu-32-core-gpu-16-core-neural-engine-36gb-memory-512gb
[apple-mini-m5-pro]: https://www.apple.com/shop/buy-mac/mac-mini/apple-m5-pro-chip-with-12-core-cpu-16-core-gpu-24gb-memory-512gb
[nvidia-grace-blackwell]: https://www.nvidia.com/en-us/data-center/technologies/blackwell-architecture/

<!-- products -->

[beelink-ai-mini]: https://x.com/Beelinkofficial/status/1920082850311029142
[beelink-gtr9-pro]: https://www.bee-link.com/en/products/beelink-gtr9-pro-amd-ryzen-ai-max-395
[corsair-ai-300]: https://www.corsair.com/us/en/p/gaming-computers/cs-9080002-na/corsair-ai-workstation-300
[dell-pro-max]: https://www.dell.com/en-us/lp/dell-pro-max-nvidia-ai-dev-premier
[framework-desktop]: https://frame.work/en/en/desktop
[gmktec-evo-x2]: https://www.gmktec.com/products/amd-ryzen%E2%84%A2-ai-max-395-evo-x2-ai-mini-pc
[hp-z2-mini]: https://www.hp.com/us-en/workstations/z2-mini-a.html
[minisforum-s1max]: https://minisforumpc.eu/products/minisforum-ms-s1-max-mini-pc
[nvidia-dgx-spark]: https://www.nvidia.com/en-us/products/workstations/dgx-spark/

## Apple Mac Mini M5 Pro

_unreleased_

## Apple Mac Studio M4 Max

- [Github / ggerganov](https://github.com/ggml-org/llama.cpp/discussions/4167) (LLM, Benchmark)
- [YouTube / Alex Ziskind](https://www.youtube.com/watch?v=ZmY35-ifJuo) (LLM, Benchmark)

## Beelink GTR9 Pro

- [ServeTheHome](https://www.servethehome.com/beelink-gtr9-pro-review-amd-ryzen-ai-max-395-system-with-128gb-and-dual-10gbe/) (Review, Disassembling, Benchmark)
- [YouTube / ServeTheHome](https://www.youtube.com/watch?v=pHB3-9AG6tw) (Review, Disassembling, LLM, Benchmark)
- [YouTube / ETA Prime](https://www.youtube.com/watch?v=t6c5RZqo6Do) (Review, Disassembling, Benchmark)

## Beelink Ai Mini

_unreleased_

## Corsair AI Workstation 300

## Dell Pro Max

## Framework Desktop

- [YouTube / Alex Ziskind](https://www.youtube.com/watch?v=ZmY35-ifJuo) (LLM, Benchmark)
- [YouTube / Jeff Geerling](https://www.youtube.com/watch?v=N5xhOqlvRh4) (LLM, Cluster, Benchmark)

## GMKtec EVO-X2

- [Notebookcheck](https://www.notebookcheck.com/Einer-der-besten-Mini-PCs-2025-AMD-Ryzen-AI-Max-395-und-Radeon-8060S-mit-mit-Top-Leistung-im-GMKtec-EVO-X2-getestet.1096325.0.html) (Review, Disassembling, Benchmark)
- [ServeTheHome](https://www.servethehome.com/gmktec-evo-x2-review-an-amd-ryzen-ai-max-395-powerhouse/) (Review, Disassembling, LLM, Benchmark)
- [YouTube / Alex Ziskind](https://www.youtube.com/watch?v=B7GDr-VFuEo) (LLM, Benchmark)
- [YouTube / ServeTheHome](https://www.youtube.com/watch?v=BTIUL-yaY4s) (Review, LLM, Benchmark)

## HP Z2 Mini G1a Workstation

- [Notebookcheck](https://www.notebookcheck.com/HP-Z2-Mini-G1a-mit-AMD-Strix-Halo-im-Test-Kompakte-Workstation-mit-Ryzen-AI-Max-und-Radeon-RX-8060S.1059460.0.html) (Review, Disassembling, Benchmark)
- [YouTube / Donato Capitella](https://www.youtube.com/watch?v=wCBLMXgk3No) (LLM, Benchmark)

## Minisforum MS-S1 Max

- [YouTube / @minisforumofficial](https://www.youtube.com/shorts/xMdFTIH5dRA) (LLM, Benchmark)
- [YouTube / ETA Prime](https://www.youtube.com/watch?v=uIjvpuFzQps) (Review, Disassembling, Benchmark)
- [YouTube / Jim's Garage](https://www.youtube.com/watch?v=LbXwXnXZNzs) (Review, Disassembling, LLM, Benchmark)
- [YouTube / Level1Techs](https://www.youtube.com/watch?v=TvNYpyA1ZGk) (Review, Disassembling, LLM, Benchmark)
- [YouTube / NASCompares](https://www.youtube.com/watch?v=8Ww2bWpVi4Q) (Review, Disassembling, Benchmark)

## NVIDIA DGX Spark

- [ServeTheHome](https://www.servethehome.com/nvidia-dgx-spark-review-the-gb10-machine-is-so-freaking-cool/) (Review, Disassembling, LLM, Benchmark)
- [YouTube / Digital Spaceport](https://www.youtube.com/watch?v=md6a4ENM9pg) (LLM, Benchmark)
- [YouTube / ServeTheHome](https://www.youtube.com/watch?v=rKOoOmIpK3I) (Review, LLM, Benchmark)
