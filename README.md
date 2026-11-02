# Референсы к Podlodka Podcast №501

Ресурсы, которые обсуждались во время выпуска о локальном AI для программирования.

- **YouTube:** «Локальный AI для программирования | DeepSeek, Qwen, ИИ агенты | Podlodka Podcast #501».
- **Аудиоверсия:** «Локальные модели для кодинга».

## Сообщества и авторы

- [Чат «ИИнтузиаст»](https://t.me/+H3uHM51jCg5mZjAy)
- [Канал «ИИнтузиаст»](https://t.me/byurrer_ru)
- [«Фарш не провернуть» — канал Алексея Фатеева о локальных моделях и инференсе](https://t.me/fuckup_files)
- [«Локальный максимум» — материалы о локальных LLM, инференсе и GPU](https://alesha.pro/)

## Модели и квантизации

- [Hugging Face — каталог моделей с открытыми весами](https://huggingface.co/models)
- [Qwen3.8-27B — основная модель, которую обсуждаем в выпуске](https://huggingface.co/Qwen/Qwen3.8-27B)
- [Qwen3.8-27B — GGUF-квантизации от Unsloth](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
- [Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)
- [GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)
- [DeepSeek V4.1 Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash-1017)
- [Gemma — документация семейства моделей Google](https://ai.google.dev/gemma/docs/core)
- [Unsloth — динамические квантизации моделей](https://unsloth.ai/blog/dynamic-v2)

## Запуск моделей и инференс

- [llama.cpp — движок для запуска локальных моделей](https://github.com/ggml-org/llama.cpp)
- [vLLM](https://github.com/vllm-project/vllm)
- [SGLang](https://github.com/sgl-project/sglang)
- [DS4 / DwarfStar — inference-движок от создателя Redis](https://github.com/antirez/ds4)
- [DeepInfer — inference-движок DeepSeek](https://github.com/deepseek-ai/DeepInfer)
- [Mirai](https://trymirai.com/)
- [Uzu — inference-движок Mirai](https://github.com/trymirai/uzu)

## Агенты и инструменты для кодинга

- [Pi — минималистичная агентская среда для работы с кодом](https://github.com/earendil-works/pi)
- [OpenCode](https://opencode.ai/v2/docs)
- [Codex](https://github.com/openai/codex)
- [Claude Code](https://github.com/anthropics/claude-code)
- [OpenClaw](https://openclaw.ai/)

## Исследования, эксперименты и кейсы

- [Coinbase — кейс дообучения Qwen3.5-9B для выявления фрода](https://www.coinbase.com/blog/part-three-owning-intelligence-series)
- [Cross-Model KV Cache Transfer — исследование переноса KV-кэша между моделями](https://arxiv.org/abs/2608.03893)
- [Экспериментальная реализация переноса KV-кэша на vLLM от Алексея Фатеева](https://github.com/alesha-pro/vllm-cross-model-kv)
- [Mostik — передача внутренних состояний между большой и маленькой моделями](https://mostik.ai/read-more)
- [Гибридный инференс с клиент-серверным разнесением prefill и decode: архитектура и экономика для клиентов с унифицированной памятью](https://github.com/relux-works/hybrid-inference-paper/releases)
- [Microsoft — локальные модели и инструменты в Windows и GitHub Copilot](https://commandline.microsoft.com/local-models-sandboxed-tools-github-windows/)
- [Microsoft — гибридный AI в Windows](https://blogs.windows.com/windowsexperience/2026/10/07/building-windows-for-hybrid-intelligence/)

## Статьи, выступления и обсуждения

- [Андрей Карпати — о разрыве между использованием чат-ботов и продвинутых агентских систем](https://x.com/karpathy/status/2109361546505966046)
- [Эссе инженера DeepSeek об автоматизации своей работы и открытом интеллекте](https://mp.weixin.qq.com/s/zk0KxuLzhmMJ4LPYW_OHMA)
- [Английский пересказ эссе инженера DeepSeek и перевод в комментариях](https://www.lesswrong.com/posts/o8roRrdisBAjngHJN/a-summary-of-a-viral-chinese-essay-on-what-a-deepseek-kernel)
- [«От вёдер к пасеке: как мы строим агентские системы» — Иван Опарин и Алексей Григорьев](https://relux.works/ru/blog/from-buckets-to-apiary/) — черновик, немного устарел; лучше посмотреть следующее выступление.
- [Рой над одной средой – Алексей Григорьев и Иван Опарин](https://www.youtube.com/watch?v=mWyUI_wZMGU)
- [Podlodka AI — сообщество опытных инженеров по AI](https://podlodka.ai/)

## Дополнительные материалы: исследования и документация

- [KV-кэш — объяснение в документации Hugging Face](https://huggingface.co/docs/transformers/en/cache_explanation)
- [Разделение prefill и decode — документация vLLM](https://docs.vllm.ai/en/latest/features/disagg_prefill/)
- [LLM-as-a-Judge — исследование оценки моделей другими моделями](https://arxiv.org/abs/2306.05685)
- [Refusal in Language Models Is Mediated by a Single Direction — исследование механизмов отказов языковых моделей](https://arxiv.org/abs/2406.11717)
- [LLaMA — оригинальная статья Meta](https://arxiv.org/abs/2302.13971)

## Дополнительные материалы: инференс

- [Создатель Redis о своём inference-движке DS4](https://antirez.com/news/165)

## Оборудование

- [NVIDIA DGX Spark](https://www.nvidia.com/en-us/products/workstations/dgx-spark/)
- [NVIDIA GeForce RTX 3090](https://www.nvidia.com/en-us/geforce/graphics-cards/30-series/rtx-3090/)
- [NVIDIA GeForce RTX 5090](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/rtx-5090/)
- [NVIDIA RTX PRO 6000 Blackwell](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/)
- [Apple Mac Studio](https://www.apple.com/mac-studio/)
- [Apple MacBook Pro](https://www.apple.com/macbook-pro/)

## Безопасность

- [eMudhra — исследование компрометации инфраструктуры сертификатов](https://emudhra.we-have-a-problem.com/)
- [PwnEscape — исследование выхода из виртуальной машины на хост](https://pwn.ai/blog/pwnescape)
- [Официальные объявления PHP об обновлениях безопасности](https://www.php.net/archive/2026.php#2026-10-21-5)

## Канал автора

- [Телеграм канал Ивана Опарина](https://t.me/tech0void)
