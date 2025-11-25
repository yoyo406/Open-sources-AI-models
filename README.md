# 🤖 Awesome Open-Source AI Models

> Une liste complète de modèles IA open-source... Parce que rien ne crie "liberté" comme du code que vous ne comprendrez de toute façon pas ! 😏✨

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📋 Table des Matières

- [Modèles de Langage (LLMs)](#-modèles-de-langage-llms)
- [Génération d'Images](#️-génération-dimages)
- [Audio / Parole / TTS](#️-audio--parole--tts)
- [Modèles Spécialisés](#-modèles-spécialisés--outils)
- [Ressources Utiles](#-ressources-utiles)
- [Récapitulatif Rapide](#-récapitulatif-rapide)
- [Contribuer](#-contribuer)

---

## 🧠 Modèles de Langage (LLMs)

*Classés par ordre alphabétique - parce que l'ordre, c'est important quand on prétend sauver le monde avec de l'IA* 🎯

### [BLOOM](https://huggingface.co/bigscience/bloom)

**Auteur:** BigScience  
**License:** RAIL License v1.0  
**Description:** Le grand frère multilingue, 100% open-source, construit par la communauté. Parce que l'union fait la force... ou au moins un README décent.

```bash
# Exemple d'utilisation
pip install transformers
```

---

### [Command R+](https://huggingface.co/CohereForAI/c4ai-command-r-plus)

**Auteur:** Cohere  
**License:** CC-BY-NC 4.0  
**Description:** Même Cohere a craqué. Open pour usage commercial, optimisé pour RAG et workflows agentiques. Les capitalistes aussi ont besoin d'amour communautaire, apparemment.

---

### [Falcon](https://huggingface.co/tiiuae/falcon-180B)

**Auteur:** TII UAE  
**License:** Custom (Apache 2.0 variant)  
**Description:** Falcon-180B était un géant... mais la licence commerciale ? Un vrai puzzle oriental 🧩

---

### [Gemma](https://ai.google.dev/gemma)

**Auteur:** Google  
**License:** Gemma Terms of Use  
**Description:** "Open source"... entre guillemets. Plutôt "open-ish". Libre comme un poisson... dans un aquarium verrouillé 🐠🔒

---

### [Llama 3](https://llama.meta.com/)

**Auteur:** Meta  
**License:** Llama 3 Community License  
**Description:** Licence semi-ouverte, usage commercial autorisé... mais avec des conditions plus floues qu'un rêve après trois Red Bulls.

```bash
# Via Ollama
ollama run llama3
```

---

### [Mistral 7B / Mixtral 8x7B / Mistral Large](https://mistral.ai/)

**Auteur:** Mistral AI  
**License:** Apache 2.0  
**Description:** Français, élégant, économe en énergie. Mixtral ? C'est comme avoir 8 cerveaux... mais un seul paie l'addition 🇫🇷💡

**Modèles disponibles:**
- Mistral 7B
- Mixtral 8x7B
- Mistral Large

---

### [OLMo](https://allenai.org/olmo)

**Auteur:** Allen Institute  
**License:** Apache 2.0  
**Description:** Le Saint Graal : code, données, logs d'entraînement - tout est public. Transparent comme votre avenir après votre cinquième café ☕

---

### [Phi-3](https://azure.microsoft.com/en-us/products/phi-3)

**Auteur:** Microsoft  
**License:** MIT  
**Description:** Petit mais costaud. Presque open... sauf qu'il faut un compte Azure pour certains poids. Tellement libre. Tellement ouvert 🙄

---

### [Qwen](https://github.com/QwenLM/Qwen)

**Auteur:** Alibaba  
**License:** Apache 2.0  
**Description:** La réponse de la Chine au reste du monde. Qwen-72B débarque en costume open-source - avec une licence étonnamment permissive 🐉

---

## 🖼️ Génération d'Images

*Pour générer des licornes cyborg en smoking... parce que le monde en a clairement besoin* 🦄🤖

### [Craiyon](https://www.craiyon.com/) (ex-DALL·E Mini)

**Auteur:** Communauté  
**License:** Apache 2.0  
**Description:** Open, oui... mais les images ressemblent à ce que votre chat dessinerait s'il avait un clavier 😹

---

### [FLUX.1](https://blackforestlabs.ai/)

**Auteur:** Black Forest Labs  
**License:** Proprietary (weights available)  
**Description:** Hyper-réaliste... mais pas *vraiment* ouvert. Désolé *mon coco* - tu restes dehors 🚪

**Variants:**
- FLUX.1 [pro] - API only
- FLUX.1 [dev] - Non-commercial
- FLUX.1 [schnell] - Apache 2.0

---

### [Kandinsky](https://github.com/ai-forever/Kandinsky-2)

**Auteur:** Sber AI  
**License:** Apache 2.0  
**Description:** Russe, open-source, et étonnamment capable. Comme une poupée russe pleine de fonctionnalités utiles... et de vodka 🪆

**Versions disponibles:**
- Kandinsky 2.2
- Kandinsky 3.0

---

### [Stable Diffusion](https://github.com/Stability-AI/stablediffusion)

**Auteur:** Stability AI  
**License:** Varies by version  
**Description:** Le classique. Poids ouverts, usage commercial souvent autorisé - mais vérifiez bien la version avant de vendre votre âme 👹

**Versions populaires:**
- SD 1.5 - CreativeML Open RAIL-M
- SDXL - OpenRAIL++-M
- SD3 - Stability AI Community License

```bash
# Avec diffusers
pip install diffusers transformers accelerate
```

---

## 🗣️ Audio / Parole / TTS

*Pour que votre IA parle avec la voix de Morgan Freeman... ou celle d'un robot dépressif* 🎙️

### [Bark](https://github.com/suno-ai/bark)

**Auteur:** Suno  
**License:** MIT  
**Description:** Génère de la parole, de la musique, des rires... parfois de manière troublante. Mais c'est open-source ! Donc c'est cool 😅

```python
from bark import generate_audio, SAMPLE_RATE

audio_array = generate_audio("Hello, I am Bark!")
```

---

### [Coqui TTS](https://github.com/coqui-ai/TTS)

**Auteur:** Communauté  
**License:** MPL 2.0  
**Description:** Framework TTS entièrement open-source. Entraînez-le sur votre propre voix - si vous osez vous écouter 🎧

```bash
# Installation
pip install TTS

# Utilisation
tts --text "Hello world!" --model_name tts_models/en/ljspeech/tacotron2-DDC
```

---

### [Whisper](https://github.com/openai/whisper)

**Auteur:** OpenAI  
**License:** MIT  
**Description:** L'ironie ultime : OpenAI nous a donné l'un des modèles les plus genuinement ouverts. Transcription audio-texte, gratuite et universelle 🎯

```bash
# Installation
pip install openai-whisper

# Utilisation
whisper audio.mp3 --model medium
```

---

## 🧪 Modèles Spécialisés & Outils

*Parce que le monde a besoin de plus que des IA qui disent "bonjour" en 42 langues* 🌍

### [Llama.cpp](https://github.com/ggerganov/llama.cpp)

**Auteur:** Georgi Gerganov  
**License:** MIT  
**Description:** Pas un modèle, mais permet de faire tourner Llama sur un grille-pain. Presque littéralement 🍞

```bash
# Build
git clone https://github.com/ggerganov/llama.cpp
cd llama.cpp && make

# Run
./main -m ./models/7B/ggml-model.bin -p "Hello world"
```

---

### [Nomic Embed](https://github.com/nomic-ai/nomic-embed)

**Auteur:** Nomic AI  
**License:** Apache 2.0  
**Description:** Embeddings ouverts ultra-compacts. Pour quand vous voulez fourrer une IA dans une disquette 💾

---

### [Sentence-Transformers](https://github.com/UKPLab/sentence-transformers)

**Auteur:** UKP Lab  
**License:** Apache 2.0  
**Description:** Loyal comme un golden retriever. Encode des phrases, ne juge jamais vos choix de vie 🐕

```python
from sentence_transformers import SentenceTransformer

model = SentenceTransformer('all-MiniLM-L6-v2')
embeddings = model.encode(['This is a sentence', 'This is another one'])
```

---

## 🔗 Ressources Utiles

*Ironiquement, pas toujours si ouvertes que ça* 😏

| Ressource | Description | Lien |
|-----------|-------------|------|
| **Hugging Face Leaderboard** | Le classement officiel des poids lourds | [→ Voir](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) |
| **Open Source AI Collective** | La communauté qui partage vraiment | [→ Voir](https://huggingface.co/open-source-ai-collective) |
| **Replicate** | Testez les modèles sans vendre un rein | [→ Voir](https://replicate.com/) |
| **Ollama Library** | Votre bibliothèque d'IA locale | [→ Voir](https://ollama.com/library) |
| **Papers with Code** | Research papers + implémentations | [→ Voir](https://paperswithcode.com/) |

---

## 📊 Récapitulatif Rapide

**Les Vraiment Ouverts** 🟢
- BLOOM, OLMo, Whisper, Stable Diffusion 1.5

**Les "Ça Dépend"** 🟡
- Llama 3, Mistral, Command R+, Qwen

**Les "Open-ish"** 🟠
- Gemma, Phi-3, FLUX.1, Falcon (licence commerciale complexe)

---

*Voilà ! C'est propre, organisé, et avec juste ce qu'il faut de sarcasme pour rendre la lecture supportable. Parce qu'un bon classement alphabétique, c'est la base de toute civilisation ! 🎩✨*
