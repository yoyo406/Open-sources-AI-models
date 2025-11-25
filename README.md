# 🤖 Awesome Open-Source AI Models

> A comprehensive list of open-source AI models... Because nothing says "freedom" quite like code you won't understand anyway! 😏✨

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📋 Table of Contents

- [Large Language Models (LLMs)](#-large-language-models-llms)
- [Image Generation](#️-image-generation)
- [Audio / Speech / TTS](#️-audio--speech--tts)
- [Specialized Models & Tools](#-specialized-models--tools)
- [Useful Resources](#-useful-resources)
- [Quick Summary](#-quick-summary)
- [Contributing](#-contributing)

---

## 🧠 Large Language Models (LLMs)

*Alphabetically sorted - because order matters when you're pretending to save the world with AI* 🎯

### [BLOOM](https://huggingface.co/bigscience/bloom)

**Author:** BigScience  
**License:** RAIL License v1.0  
**Description:** The multilingual big sibling, 100% open-source, built by the community. Because unity makes strength... or at least a decent README.

```bash
# Example usage
pip install transformers
```

---

### [Command R+](https://huggingface.co/CohereForAI/c4ai-command-r-plus)

**Author:** Cohere  
**License:** CC-BY-NC 4.0  
**Description:** Even Cohere cracked. Open for commercial use, optimized for RAG and agentic workflows. Turns out capitalists need community love too.

---

### [Falcon](https://huggingface.co/tiiuae/falcon-180B)

**Author:** TII UAE  
**License:** Custom (Apache 2.0 variant)  
**Description:** Falcon-180B was a giant... but the commercial license? A real oriental puzzle 🧩

---

### [Gemma](https://ai.google.dev/gemma)

**Author:** Google  
**License:** Gemma Terms of Use  
**Description:** "Open source"... in quotes. More like "open-ish". Free as a fish... in a locked aquarium 🐠🔒

---

### [Llama 3](https://llama.meta.com/)

**Author:** Meta  
**License:** Llama 3 Community License  
**Description:** Semi-open license, commercial use allowed... but with terms vaguer than a dream after three Red Bulls.

```bash
# Via Ollama
ollama run llama3
```

---

### [Mistral 7B / Mixtral 8x7B / Mistral Large](https://mistral.ai/)

**Author:** Mistral AI  
**License:** Apache 2.0  
**Description:** French, elegant, and energy-efficient. Mixtral? It's like having 8 brains... but only one pays the bill 🇫🇷💡

**Available models:**
- Mistral 7B
- Mixtral 8x7B
- Mistral Large

---

### [OLMo](https://allenai.org/olmo)

**Author:** Allen Institute  
**License:** Apache 2.0  
**Description:** The holy grail: code, data, training logs—everything's public. Transparent as your future after your fifth coffee ☕

---

### [Phi-3](https://azure.microsoft.com/en-us/products/phi-3)

**Author:** Microsoft  
**License:** MIT  
**Description:** Small but mighty. Almost open... except you need an Azure account for some weights. So free. So open 🙄

---

### [Qwen](https://github.com/QwenLM/Qwen)

**Author:** Alibaba  
**License:** Apache 2.0  
**Description:** China's answer to the rest of the world. Qwen-72B struts in wearing an open-source suit—with a surprisingly permissive license 🐉

---

## 🖼️ Image Generation

*For generating cyborg unicorns in tuxedos... because the world clearly needs that* 🦄🤖

### [Craiyon](https://www.craiyon.com/) (formerly DALL·E Mini)

**Author:** Community  
**License:** Apache 2.0  
**Description:** Open, yes... but the images look like what your cat would draw if it had a keyboard 😹

---

### [FLUX.1](https://blackforestlabs.ai/)

**Author:** Black Forest Labs  
**License:** Proprietary (weights available)  
**Description:** Hyper-realistic... but not *truly* open. Sorry *buddy* - you're staying outside 🚪

**Variants:**
- FLUX.1 [pro] - API only
- FLUX.1 [dev] - Non-commercial
- FLUX.1 [schnell] - Apache 2.0

---

### [Kandinsky](https://github.com/ai-forever/Kandinsky-2)

**Author:** Sber AI  
**License:** Apache 2.0  
**Description:** Russian, open-source, and surprisingly capable. Like a matryoshka doll full of useful features... and vodka 🪆

**Available versions:**
- Kandinsky 2.2
- Kandinsky 3.0

---

### [Stable Diffusion](https://github.com/Stability-AI/stablediffusion)

**Author:** Stability AI  
**License:** Varies by version  
**Description:** The classic. Open weights, commercial use often allowed - but double-check the version before selling your soul 👹

**Popular versions:**
- SD 1.5 - CreativeML Open RAIL-M
- SDXL - OpenRAIL++-M
- SD3 - Stability AI Community License

```bash
# With diffusers
pip install diffusers transformers accelerate
```

---

## 🗣️ Audio / Speech / TTS

*So your AI can talk in Morgan Freeman's voice... or that of a depressed robot* 🎙️

### [Bark](https://github.com/suno-ai/bark)

**Author:** Suno  
**License:** MIT  
**Description:** Generates speech, music, laughter... sometimes hauntingly. But it's open-source! So it's cool 😅

```python
from bark import generate_audio, SAMPLE_RATE

audio_array = generate_audio("Hello, I am Bark!")
```

---

### [Coqui TTS](https://github.com/coqui-ai/TTS)

**Author:** Community  
**License:** MPL 2.0  
**Description:** Fully open-source TTS framework. Train it on your own voice - if you dare to listen to yourself 🎧

```bash
# Installation
pip install TTS

# Usage
tts --text "Hello world!" --model_name tts_models/en/ljspeech/tacotron2-DDC
```

---

### [Whisper](https://github.com/openai/whisper)

**Author:** OpenAI  
**License:** MIT  
**Description:** The ultimate irony: OpenAI gave us one of the most genuinely open models. Audio-to-text transcription, free and everywhere 🎯

```bash
# Installation
pip install openai-whisper

# Usage
whisper audio.mp3 --model medium
```

---

## 🧪 Specialized Models & Tools

*Because the world needs more than just AIs that say "hello" in 42 languages* 🌍

### [Llama.cpp](https://github.com/ggerganov/llama.cpp)

**Author:** Georgi Gerganov  
**License:** MIT  
**Description:** Not a model, but lets you run Llama on a toaster. Almost literally 🍞

```bash
# Build
git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp && make

# Run
./main -m ./models/7B/ggml-model.bin -p "Hello world"
```

---

### [Nomic Embed](https://github.com/nomic-ai/nomic-embed)

**Author:** Nomic AI  
**License:** Apache 2.0  
**Description:** Ultra-compact open embeddings. For when you want to shove an AI into a floppy disk 💾

---

### [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers)

**Author:** UKP Lab  
**License:** Apache 2.0  
**Description:** Loyal as a golden retriever. Encodes sentences, never judges your life choices 🐕

```python
from sentence_transformers import SentenceTransformer

model = SentenceTransformer('all-MiniLM-L6-v2')
embeddings = model.encode(['This is a sentence', 'This is another one'])
```

---

## 🔗 Useful Resources

*Ironically, not always that open* 😏

| Resource | Description | Link |
|----------|-------------|------|
| **Hugging Face Leaderboard** | The official heavyweight championship | [→ Visit](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) |
| **Open Source AI Collective** | The community that actually shares | [→ Visit](https://huggingface.co/open-source-ai-collective) |
| **Replicate** | Test models without selling a kidney | [→ Visit](https://replicate.com/) |
| **Ollama Library** | Your local AI library | [→ Visit](https://ollama.com/library) |
| **Papers with Code** | Research papers + implementations | [→ Visit](https://paperswithcode.com/) |

---

## 📊 Quick Summary

### 🟢 The Truly Open Ones
*Permissive license + code + weights available*

- ✅ **BLOOM** - BigScience (RAIL License)
- ✅ **OLMo** - Allen Institute (Apache 2.0)
- ✅ **Whisper** - OpenAI (MIT)
- ✅ **Stable Diffusion 1.5** - Stability AI (CreativeML OpenRAIL-M)
- ✅ **Mistral 7B** - Mistral AI (Apache 2.0)
- ✅ **Llama.cpp** - Georgi Gerganov (MIT)

### 🟡 The "It Depends"
*Available but with commercial restrictions*

- ⚠️ **Llama 3** - Meta (Community License)
- ⚠️ **Command R+** - Cohere (CC-BY-NC 4.0)
- ⚠️ **Qwen** - Alibaba (Apache 2.0 but...)
- ⚠️ **Mixtral** - Mistral AI (Apache 2.0)

### 🟠 The "Open-ish"
*"Open source" with a giant asterisk*

- ⛔ **Gemma** - Google (Proprietary Terms of Use)
- ⛔ **Phi-3** - Microsoft (MIT but restricted weights)
- ⛔ **FLUX.1** - Black Forest Labs (weights available, restrictive license)
- ⛔ **Falcon** - TII UAE (complex commercial license)

---

## 🤝 Contributing

Contributions are welcome! To add a model:

1. **Fork** this repo
2. **Create** a branch (`git checkout -b feature/new-model`)
3. **Add** your model following the existing format
4. **Commit** your changes (`git commit -am 'Add [Model Name]'`)
5. **Push** to the branch (`git push origin feature/new-model`)
6. **Create** a Pull Request

### Inclusion Criteria

For a model to be added, it must:
- ✅ Have publicly available weights
- ✅ Have clear documentation
- ✅ Be usable without major barriers
- ✅ Have an active community (bonus)

---

## 📜 License

This repo is under [MIT](LICENSE) license - Because even sarcastic lists deserve to be free! 🆓

---

## ⭐ Star History

If this repo was helpful, feel free to give it a star! ⭐

*Because a good alphabetical sorting is the foundation of civilization!* 🎩✨

---

**Last updated:** November 2025  
**Maintained by:** The community (and lots of coffee ☕)
