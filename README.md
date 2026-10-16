# Hello

CS student. Knows a bit about reverse engineering, game plugins, AI agent tools and some systems programming.

I mostly write Python, C/C++ and C#.

## Projects

- [PolyStrata](https://github.com/VecSzn/PolyStrata) ![stars](https://img.shields.io/github/stars/VecSzn/PolyStrata?style=flat) - runs large open models on an ordinary PC behind a local OpenAI/Anthropic API. It is built on [Strata](https://github.com/Niko1221/Strata); I wrote its second engine, which runs eight MoE models (GLM 5.3 Flash, DeepSeek V4 Flash, LFM2.5, Qwen3.6, Gemma 4 and others) and decides which experts sit in VRAM and which run on the CPU. On a laptop with an 8 GB card it writes 94-100 tokens/s with Qwen3.6-35B-A3B, 1.5 to 1.8 times as fast as llama.cpp.
- [lobes](https://github.com/VecSzn/lobes) ![stars](https://img.shields.io/github/stars/VecSzn/lobes?style=flat) - an experiment in splitting one local assistant into a few small models, each with one job, on a single consumer GPU.

## Contributed to

- [ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) ![stars](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp?style=flat) - three bug fixes: string arguments were being JSON-decoded by mistake, `count=0` returned 100 rows instead of all of them, and immediate search missed 32-bit constants with the top bit set.
- [kev](https://github.com/jaredpalmer/kev) ![stars](https://img.shields.io/github/stars/jaredpalmer/kev?style=flat) - fixed `--init-from` failing on a run name from the volume (only Hub ids worked).
- [cpp-httplib](https://github.com/yhirose/cpp-httplib) ![stars](https://img.shields.io/github/stars/yhirose/cpp-httplib?style=flat) - the client now resolves relative `Location` values when it follows a redirect.
