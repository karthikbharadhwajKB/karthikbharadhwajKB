<div align="center">

# Karthik Kolluri

**PhD Researcher, University of Essex · AI Engineer (NLP), Hivedome Ltd.**<br>
Compression, distillation, and fairness in speech and audio language models<br>
<sub>Ganesh Pavan Kartikeya Bharadwaj Kolluri (G. P. K. B. Kolluri)</sub>

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-34699A?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=mIv1JY0AAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-34699A?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D)](https://www.linkedin.com/in/karthik-bharadhwaj-1998kb/)
[![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-34699A?style=flat-square&logo=semanticscholar&logoColor=white)](https://www.semanticscholar.org/author/Ganesh-Pavan-Kartikeya-Bharadwaj-Kolluri/2426796570)
[![ORCID](https://img.shields.io/badge/ORCID-34699A?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-8549-4474)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-34699A?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/KarthikKB1998)
[![Email](https://img.shields.io/badge/Email-34699A?style=flat-square&logo=gmail&logoColor=white)](mailto:karthikbharadhwaj1998@gmail.com)

</div>

I compress speech and audio language models and measure what is lost, how much can be recovered, whether all speakers lose equally, and whether the encoder can be removed altogether. I am a PhD researcher at the University of Essex and an AI Engineer (NLP) at Hivedome Ltd., and before that I was a Machine Learning Engineer at Eidosmedia in Milan.

## Publications

**CARD: Cross-component Audio Representation Distillation for Encoder-Free Audio Captioning**<br>
**G. P. K. B. Kolluri**, Y. Zhang, M. Kampouridis, R. Shekhar · *IEEE SLT 2026* (to appear)<br>
An audio captioning model with no audio encoder at inference. During training, a pretrained audio teacher is distilled into two components: its perceptual stages into a small projector and its semantic stages into the language model.<br>
[arXiv](https://arxiv.org/abs/2607.04619) · [Code](https://github.com/karthikbharadhwajKB/CARD) · [Models](https://huggingface.co/collections/KarthikKB1998/card-encoder-free-audio-captioning-ieee-slt-2026-6aab0d5d46f574fd376ff1d7) · [Demo](https://huggingface.co/spaces/KarthikKB1998/CARD-Audio-Captioning)

**Pruning for Efficiency, Paying in Fairness: Demographic Disparities in Pruned Speech-LLMs**<br>
**G. P. K. B. Kolluri**, M. Kampouridis, R. Shekhar · *IMPACT-SPEECH Workshop at EMNLP 2026* (oral, to appear)<br>
Compression results are usually reported as one average error rate. This paper measures how pruning a speech language model changes recognition error for each demographic group of speakers.<br>
[Code](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness)

**On the Role of Encoder Depth: Pruning Whisper and LoRA Fine-Tuning in SLAM-ASR**<br>
**G. P. K. B. Kolluri**, M. Kampouridis, R. Shekhar · *Proc. SPEAKABLE Workshop at LREC 2026*<br>
Layer pruning of the Whisper encoder within SLAM-ASR: how word error rate changes with encoder depth, and how far LoRA fine-tuning of the language model recovers the loss.<br>
[ACL Anthology](https://aclanthology.org/2026.speakable-1.20/) · [arXiv](https://arxiv.org/abs/2603.27981) · [Code](https://github.com/karthikbharadhwajKB/SLAM-ASR-Encoder-Pruning-LoRA)

## Projects

### Industry

- **ASK ITAS** · Hivedome Ltd., 2025–present<br>
  An agentic AI assistant for ITAS, Hivedome's commodity trading and risk management platform. Users ask in plain language and get answers with sources. An LLM plans each answer and uses tools for knowledge-base search, live Data Portal queries, and clarifying questions.<br>
  *LLM agents · tool use · RAG · AWS*
- **Retrieval-augmented question answering for news publishers** · Eidosmedia, 2023–2025<br>
  Editorial staff ask questions and get answers, with citations, from a large newspaper archive.<br>
  *Python · semantic search · LangChain · AWS*
- **Autonomous newspaper pagination** · Eidosmedia, 2022–2024<br>
  Places articles on a page from an editorial page plan. It began as my MSc thesis at the University of Bologna, was trained and evaluated on a corpus of published newspapers built for the purpose, and went into production.<br>
  *Reinforcement learning · dataset construction*

### Research code

- [**CARD**](https://github.com/karthikbharadhwajKB/CARD): distillation and fine-tuning, inference, and checkpoints on the Hugging Face Hub for the IEEE SLT 2026 paper.
- [**SpeechLLM-Pruning-Fairness**](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness): encoder pruning, projector retraining, and per-group evaluation on Common Voice and Fair-Speech.
- [**SLAM-ASR-Encoder-Pruning-LoRA**](https://github.com/karthikbharadhwajKB/SLAM-ASR-Encoder-Pruning-LoRA): code and configurations for the LREC 2026 SPEAKABLE paper on encoder depth.

### Open source

- [**PaperReady**](https://github.com/karthikbharadhwajKB/PaperReady): web app that cleans LaTeX projects for arXiv and checks ACL papers with aclpubcheck.
- [**Agents**](https://github.com/karthikbharadhwajKB/Agents): AI agent examples on the OpenAI Agents SDK, covering Gmail, Notion, YouTube, and an MCP server.
- [**Langchain_OpenSearch_Hybrid_search**](https://github.com/karthikbharadhwajKB/Langchain_OpenSearch_Hybrid_search): hybrid (keyword and vector) and full-text search for LangChain's OpenSearch vector store.
- [**Audio-LLMs**](https://github.com/karthikbharadhwajKB/Audio-LLMs): prototype ASR model that connects a Whisper encoder to an LLM.

## Skills

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,dart,flutter,bash,linux,git,github,aws,latex&theme=dark" alt="Python, PyTorch, TensorFlow, scikit-learn, Dart, Flutter, Bash, Linux, Git, GitHub, AWS, LaTeX" />
</p>

| Area | Tools |
| :--- | :--- |
| Languages | Python, Dart, Bash, LaTeX |
| Deep learning | PyTorch, Hugging Face Transformers, PEFT / LoRA, TensorFlow / Keras, scikit-learn |
| Speech and audio | Whisper, SLAM-ASR, Common Voice |
| LLMs and agents | LangChain, OpenAI Agents SDK, Model Context Protocol (MCP), Ollama, Unsloth / TRL, RAG |
| Retrieval | OpenSearch, Chroma, FAISS |
| Infrastructure and tools | AWS, Weights & Biases, uv, Git, Streamlit, Flutter, Jupyter |
