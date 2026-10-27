# Open Source Ai Models

**English** | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

The best open-source AI models — LLMs, vision, audio, multimodal

## 🧠 LLMs (open weights)
| Model | Sizes | Note |
|---|---|---|
| Llama 3.x / 4 | 1B–400B+ | Meta — the ecosystem default |
| Qwen 2.5 / 3 | 0.5B–235B | Best multilingual & coding density |
| DeepSeek V3/R1 | 671B MoE | Frontier reasoning, open weights |
| Mistral / Mixtral | 7B–123B | Efficient, 🇫🇷, Apache-licensed smaller ones |
| Gemma 2/3 | 1B–27B | Google's compact open weights |
| Phi-4 | 14B | Microsoft — small & sharp |

## 🖼️ Image
| Model | Note |
|---|---|
| Flux.1 [schnell/dev] | Black Forest Labs — open, fast, great quality |
| SD 3.5 / SDXL | The classic base |
| Stable Cascade | Older but capable |
| Playground v2.5 | Aesthetic-focused |

## 🔊 Audio
| Model | Note |
|---|---|
| Whisper v3 / turbo | ASR standard |
| MusicGen | Meta music generation |
| XTTS v2 | Voice cloning (Coqui archive) |
| SeamlessM4T | Meta speech-to-speech translation |

## 👁️ Vision / multimodal
| Model | Note |
|---|---|
| Qwen2-VL / 2.5-VL | Strong doc/UI understanding |
| Llava / Llava-Next | Popular VLM family |
| InternVL | Strong multimodal |
| SAM 2 | Segmentation for images & video |

## 📦 Where to get them
- [HuggingFace](https://huggingface.co/models) — the hub
- [Ollama library](https://ollama.com/library) — one-command local runs
- [Replicate](https://replicate.com/) — cloud API for open models

## 🏆 Open weights leaderboard (practical)

| Model | Params | License | Best at |
|---|---|---|---|
| Llama 3.3 70B | 70B | Llama | General |
| Qwen 2.5 72B | 72B | Apache-ish | Coding/multilingual |
| DeepSeek V3 | 671B MoE | MIT | Frontier-adjacent |
| Mistral Large | 123B | Research | European option |
| Gemma 2 27B | 27B | Gemma | Efficiency |
| Phi-4 | 14B | MIT | Reasoning-per-param |

## 🎯 Task picks

| Need | Pick |
|---|---|
| Code | Qwen2.5-Coder 32B |
| Vision | Qwen2-VL, Llama 3.2 Vision |
| Math | DeepSeek-R1 distilled |
| Tiny | Phi-4-mini, Llama 3.2 1-3B |
| Uncensored fine-tunes | Community merges on HF |

---
Maintained by [aixisstudio](https://github.com/aixisstudio) — author of [Snitch](https://github.com/aixisstudio/Snitch), the open-source application firewall.

## License

MIT
