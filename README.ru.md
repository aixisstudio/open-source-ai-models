# Open Source Ai Models

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Лучшие open-source ИИ-модели

## ) LLM (открытые веса)
Обсуждение Sizes | Note
|---|---|---|
Ллама 3.x / 4 | 1B-400B + | Мета — экосистема по умолчанию |
Qwen 2.5 / 3 | 0,5B-235B | Лучшая многоязычная и кодирующая плотность
DeepSeek V3/R1 | 671B MoE | Пограничные рассуждения, открытые веса |
| Mistral / Mixtral | 7B-123B | Эффективные,  , лицензированные Apache
Gemma 2/3 | 1B-27B | Компактные открытые веса Google
Phi-4 | 14B | Microsoft — маленький и острый

##  ️ Изображение
Модель, примечание
|---|---|
| Flux.1 [schnell/dev] | Лаборатории Чёрного леса — открытые, быстрые, отличного качества |
SD 3.5 / SDXL Классическая база.
Стабильный каскад Старый, но способный
Игровая площадка v2.5 | Эстетически ориентированный

###Аудио
Модель, примечание
|---|---|
| Шепот v3/турбо | Стандарт ASR |
Музыкальное поколение Meta Music Generation
XTTS v2 клонирование голоса (архив Коки)
SeamlessM4T - перевод речи на речь

##  ️ Видение / мультимодальный
Модель, примечание
|---|---|
| Qwen2-VL / 2.5-VL | Сильное понимание doc/UI |
Llava / Llava-Next | Популярное семейство VLM
[править] Сильная мультимодальность
| SAM 2 | Сегментация изображений и видео

### Где их взять
- [HuggingFace] (https://huggingface.co/models) - концентратор
- [Библиотека Олламы] (https://ollama.com/library) - однокомандные локальные прогоны
[Replicate] (https://replicate.com/) — облачный API для открытых моделей

## ) Открытая таблица весов (практическая)

Модель, Парамс, Лицензия, Лучшее в
|---|---|---|---|
3.3 70B | 70B | Llama | General |
| Qwen 2.5 72B | 72B | Apache-ish | Кодирование/многоязычное |
DeepSeek V3 | 671B MoE | MIT | Frontier-adjacent |
| Mistral Large | 123B | Исследования | Европейский вариант
Gemma 2 27B | 27B | Gemma | Эффективность
Phi-4 | 14B | MIT | Reasoning-per-param |

###Выбор задач

Оригинальное название: Need | Pick
|---|---|
Код Qwen2.5-Coder 32B
Qwen2-VL, Llama 3.2 Видение.
Дистилляция DeepSeek-R1
| Крошечные | Phi-4-mini, Llama 3.2 1-3B |
| Без цензуры тонкой настройки | Сообщество сливается на HF |

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
