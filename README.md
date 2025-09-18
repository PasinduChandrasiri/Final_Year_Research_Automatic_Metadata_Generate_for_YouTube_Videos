# 🎬 Multimodal Metadata Magic: Enhancing YouTube Video Discoverability

Welcome to the official repository for our final year research, **"Enhancing Automatic Metadata Generation for YouTube Videos through Multimodal Contextual Analysis."** This project unlocks smarter, AI-driven metadata that boosts video reach, audience targeting, and automates the tedious work for creators—all using the latest advances in multimodal AI and language models.

## 🚀 Project Overview

YouTube thrives on metadata: titles, tags, and descriptions shape what the world watches next. Yet, manual metadata creation is time-consuming, inconsistent, and not contextually rich. Our research charts a new course by merging video, audio, and transcript cues using custom fusion pipelines and cutting-edge language models to **automatically generate accurate, context-aware metadata**—elevating both video discovery and creator productivity.

## 🧠 What Sets Us Apart

- **Multimodal Brilliance:** We unify video frames (ResNeXt-101), audio fingerprints (MFCC), and text transcripts (Whisper) to deeply understand and summarize content.
- **Smart RAG Architecture:** Powered by **LLaMA3 7B** integrated via **Ollama** within a Retrieval-Augmented Generation (RAG) pipeline, enabling real-time, contextual metadata generation using Pinecone vector databases—no retraining required for new uploads.
- **Hands-off for Creators:** A seamless backend API and Chrome extension let users auto-populate YouTube upload forms with top-notch metadata, reducing friction and maximizing discoverability.
- **Custom Data Pipeline:** Built on an expanded MSR-VTT dataset (8,811+ video clips, human-annotated), ensuring robust multimodal evaluation and adaptation to diverse video genres.

## 🔬 Methodology Snapshot

- **Data Curation & Features:** Video, audio, and text transcriptions are extracted, validated, and fused with human-written captions for reference.
- **Fusion & Retrieval:** Multimodal embeddings are indexed via Pinecone, supporting dynamic real-time retrieval and fusion inside the LLaMA3 pipeline.
- **Automation:** The Chrome extension hooks seamlessly into YouTube's Studio workflow, sending data to our backend for metadata prediction and form population—no more manual copy-paste.

## 📈 Achievements So Far

- **End-to-end operational system**: From dataset preprocessing and feature extraction to live Chrome extension deployment.
- **Qualitative improvements**: Early tests show our system consistently produces fluent, relevant, and context-specific metadata.
- **Adaptability and scalability**: Our RAG approach adapts to new content without model retraining, keeping up with the fast-paced world of video uploads.

## 🧩 Challenges Met

- Dynamic metadata generation solved via RAG and Pinecone, beating the need for repeated expensive model training.
- Reliable multimodal feature validation and rigorous dataset integrity checking.
- Real-world automation through a custom Chrome extension that makes the technology accessible to creators.

## 🛠️ Next Up

- Improve multimodal fusion using hierarchical cross-modal attention.
- Automate YouTube Studio field population for an even smoother workflow.
- Expand to a larger and more diverse video dataset for broader domain coverage.
- Implement retrieval reranking and formal evaluation (BLEU, ROUGE, F1).

## ✨ Meet the Researchers

| Name                | Role                   | LinkedIn                                                    |
|---------------------|------------------------|-------------------------------------------------------------|
| KULATHUNGA K.M.P.S  | Data & Extension Lead  | [LinkedIn](https://www.linkedin.com/in/pramuda-kulathunga)  |
| CHANDRASIRI P.G.P.M | AI & Backend Lead      | [LinkedIn](https://www.linkedin.com/in/pasinduchandrasiri)  |

## 📬 Contact

For collaboration, feedback, or queries, drop us a message via LinkedIn!

---

Ignite the future of YouTube with smarter, scalable, and contextually-aware video metadata—powered by multimodal AI.
