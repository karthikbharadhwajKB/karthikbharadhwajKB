<div align="center">

# Karthik Kolluri

**PhD Researcher @ University of Essex | AI Engineer (NLP) @ Hivedome**<br>
*Efficient Speech & Audio AI · Multimodal LLMs · Applied AI Systems*

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=mIv1JY0AAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D)](https://www.linkedin.com/in/karthik-bharadhwaj-1998kb/)
[![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-1857B6?style=flat&logo=semanticscholar&logoColor=white)](https://www.semanticscholar.org/author/Ganesh-Pavan-Kartikeya-Bharadwaj-Kolluri/2426796570)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-8549-4474)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/KarthikKB1998)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:karthikbharadhwaj1998@gmail.com)

</div>

I research how to make speech and audio language models more efficient while understanding the trade-offs in accuracy and fairness. My work explores encoder pruning, LoRA adaptation, and knowledge distillation, from recovering performance after compression to developing encoder-free audio captioning models.

Alongside my PhD, I develop applied AI systems involving retrieval-augmented generation (RAG), LLM agents, and tool-integrated workflows. Previously, at Eidosmedia, I worked on domain-adapted language models and production machine learning systems for digital publishing.

## Featured work

| Project | What it demonstrates | Links |
| :--- | :--- | :--- |
| [**CARD**](https://github.com/karthikbharadhwajKB/CARD) | Novel research and model design: encoder-free audio captioning through cross-component distillation, with released models and a working demo | [Code](https://github.com/karthikbharadhwajKB/CARD) · [Models](https://huggingface.co/collections/KarthikKB1998/card-encoder-free-audio-captioning-ieee-slt-2026-6aab0d5d46f574fd376ff1d7) · [Demo](https://huggingface.co/spaces/KarthikKB1998/CARD-Audio-Captioning) |
| [**SpeechLLM-Pruning-Fairness**](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness) | Rigorous evaluation and responsible compression: encoder pruning, projector retraining, and per-group evaluation on Fair-Speech and Common Voice | [Code](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness) · [Paper](https://arxiv.org/abs/2609.38106) |
| [**Agents**](https://github.com/karthikbharadhwajKB/Agents) | Practical LLM agents and integrations on the OpenAI Agents SDK: Gmail, Notion, YouTube, and an MCP server | [Code](https://github.com/karthikbharadhwajKB/Agents) |

## Publications

### CARD: Cross-component Audio Representation Distillation for Encoder-Free Audio Captioning
*IEEE SLT 2026 · Accepted* · **G. P. K. B. Kolluri**, Y. Zhang, M. Kampouridis, R. Shekhar

Encoder-free audio captioning through cross-component knowledge distillation.<br>
**Key result:** a 13.2M-parameter projector replaces the audio encoder at inference and improves CIDEr-D by 11.9 points over an LLM-only distillation baseline on AudioCaps (+5.0 on Clotho).<br>
[Paper](https://arxiv.org/abs/2607.04619) · [Code](https://github.com/karthikbharadhwajKB/CARD) · [Models](https://huggingface.co/collections/KarthikKB1998/card-encoder-free-audio-captioning-ieee-slt-2026-6aab0d5d46f574fd376ff1d7) · [Demo](https://huggingface.co/spaces/KarthikKB1998/CARD-Audio-Captioning)

### Pruning for Efficiency, Paying in Fairness: Demographic Disparities in Pruned Speech-LLMs
*IMPACT-SPEECH Workshop @ EMNLP 2026 · Accepted (oral)* · **G. P. K. B. Kolluri**, M. Kampouridis, R. Shekhar

Per-group evaluation of audio-encoder pruning in SLAM-ASR on Fair-Speech and Common Voice.<br>
**Key result:** pruning does not affect all demographic groups equally. The gap between the best- and worst-performing groups widens, and aggregate WER can hide it; LoRA adaptation helps every group but benefits the best-performing groups most.<br>
[Paper](https://arxiv.org/abs/2609.38106) · [Code](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness)

### On the Role of Encoder Depth: Pruning Whisper and LoRA Fine-Tuning in SLAM-ASR
*SPEAKABLE Workshop @ LREC 2026 · Published* · **G. P. K. B. Kolluri**, M. Kampouridis, R. Shekhar

Layer pruning of the Whisper encoder in SLAM-ASR across three model sizes and three languages.<br>
**Key result:** pruning two encoder layers costs only 2–4% WER, and adding LoRA adaptation outperforms the unpruned baseline while cutting total parameters by 7–14%.<br>
[ACL Anthology](https://aclanthology.org/2026.speakable-1.20/) · [arXiv](https://arxiv.org/abs/2603.27981) · [Code](https://github.com/karthikbharadhwajKB/SLAM-ASR-Encoder-Pruning-LoRA)

## Industry experience

**ASK ITAS | Hivedome Ltd. | 2025–present**<br>
Developing an AI assistant for ITAS, a commodity trading and risk management platform, through a Knowledge Transfer Partnership with the University of Essex. The initial release focuses on knowledge-base question answering with source references. An agentic architecture supporting tool-driven Data Portal queries and clarification workflows is under development.<br>
*LLM Agents · RAG · Tool Calling · AWS*

**Machine Learning Engineer | Eidosmedia, Milan | 2022–2025**
- Retrieval-augmented question answering for news publishers, with answers drawn from a large newspaper archive and citations to the source articles.
- Domain-adapted language models for the publishing industry, with training and deployment pipelines on AWS.
- Autonomous newspaper pagination: a reinforcement learning system that places articles on a page from an editorial plan. It began as my MSc thesis and went into production.

*RAG · Semantic Search · LangChain · Reinforcement Learning · AWS*

## Additional repositories

| Repository | Description |
| :--- | :--- |
| [**SLAM-ASR-Encoder-Pruning-LoRA**](https://github.com/karthikbharadhwajKB/SLAM-ASR-Encoder-Pruning-LoRA) | Whisper encoder pruning and LoRA recovery in SLAM-ASR (SPEAKABLE, LREC 2026) |
| [**PaperReady**](https://github.com/karthikbharadhwajKB/PaperReady) | Web app that cleans LaTeX projects for arXiv and checks ACL papers with aclpubcheck |
| [**Langchain_OpenSearch_Hybrid_search**](https://github.com/karthikbharadhwajKB/Langchain_OpenSearch_Hybrid_search) | Hybrid (keyword and vector) and full-text search for LangChain's OpenSearch vector store |
| [**Audio-LLMs**](https://github.com/karthikbharadhwajKB/Audio-LLMs) | Prototype ASR model that connects a Whisper encoder to an LLM |

## Technical expertise

| Area | Technologies |
| :--- | :--- |
| Programming | [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org) [![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/) |
| Deep Learning | [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org) [![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/docs/transformers) [![PEFT / LoRA](https://img.shields.io/badge/PEFT_%2F_LoRA-FF9D00?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/docs/peft) |
| Speech & Audio AI | [![Whisper](https://img.shields.io/badge/Whisper-10A37F?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjEiIHk9IjkiIHdpZHRoPSIyLjQiIGhlaWdodD0iNiIgcng9IjEuMiIvPjxyZWN0IHg9IjUuNCIgeT0iNSIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIxNCIgcng9IjEuMiIvPjxyZWN0IHg9IjkuOCIgeT0iMiIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIyMCIgcng9IjEuMiIvPjxyZWN0IHg9IjE0LjIiIHk9IjYiIHdpZHRoPSIyLjQiIGhlaWdodD0iMTIiIHJ4PSIxLjIiLz48cmVjdCB4PSIxOC42IiB5PSI5IiB3aWR0aD0iMi40IiBoZWlnaHQ9IjYiIHJ4PSIxLjIiLz48L3N2Zz4%3D)](https://github.com/openai/whisper) [![SLAM-ASR](https://img.shields.io/badge/SLAM--ASR-7C3AED?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjEiIHk9IjkiIHdpZHRoPSIyLjQiIGhlaWdodD0iNiIgcng9IjEuMiIvPjxyZWN0IHg9IjUuNCIgeT0iNSIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIxNCIgcng9IjEuMiIvPjxyZWN0IHg9IjkuOCIgeT0iMiIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIyMCIgcng9IjEuMiIvPjxyZWN0IHg9IjE0LjIiIHk9IjYiIHdpZHRoPSIyLjQiIGhlaWdodD0iMTIiIHJ4PSIxLjIiLz48cmVjdCB4PSIxOC42IiB5PSI5IiB3aWR0aD0iMi40IiBoZWlnaHQ9IjYiIHJ4PSIxLjIiLz48L3N2Zz4%3D)](https://github.com/X-LANCE/SLAM-LLM) [![Audio LLMs](https://img.shields.io/badge/Audio_LLMs-0891B2?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjEiIHk9IjkiIHdpZHRoPSIyLjQiIGhlaWdodD0iNiIgcng9IjEuMiIvPjxyZWN0IHg9IjUuNCIgeT0iNSIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIxNCIgcng9IjEuMiIvPjxyZWN0IHg9IjkuOCIgeT0iMiIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIyMCIgcng9IjEuMiIvPjxyZWN0IHg9IjE0LjIiIHk9IjYiIHdpZHRoPSIyLjQiIGhlaWdodD0iMTIiIHJ4PSIxLjIiLz48cmVjdCB4PSIxOC42IiB5PSI5IiB3aWR0aD0iMi40IiBoZWlnaHQ9IjYiIHJ4PSIxLjIiLz48L3N2Zz4%3D)](https://github.com/karthikbharadhwajKB/Audio-LLMs) |
| LLM Applications | [![RAG](https://img.shields.io/badge/RAG-2F81F7?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTAiIGN5PSIxMCIgcj0iNi41IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIuOCIvPjxwYXRoIGQ9Ik0xNSAxNWw2LjUgNi41IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjMiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPjwvc3ZnPg%3D%3D)](https://arxiv.org/abs/2005.11401) [![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)](https://www.langchain.com) [![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMTEiIHk9IjEuNSIgd2lkdGg9IjIiIGhlaWdodD0iNSIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjIuNSIgcj0iMS44IiBmaWxsPSJ3aGl0ZSIvPjxyZWN0IHg9IjMiIHk9IjYuNSIgd2lkdGg9IjE4IiBoZWlnaHQ9IjE0IiByeD0iNCIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSI4LjUiIGN5PSIxMyIgcj0iMiIgZmlsbD0iIzQxMjk5MSIvPjxjaXJjbGUgY3g9IjE1LjUiIGN5PSIxMyIgcj0iMiIgZmlsbD0iIzQxMjk5MSIvPjwvc3ZnPg%3D%3D)](https://openai.github.io/openai-agents-python/) [![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat-square&logo=modelcontextprotocol&logoColor=white)](https://modelcontextprotocol.io) |
| Retrieval | [![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)](https://opensearch.org) [![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)](https://github.com/facebookresearch/faiss) [![Chroma](https://img.shields.io/badge/Chroma-F97316?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0zIDVjMC0xLjkgNC0zLjUgOS0zLjVzOSAxLjYgOSAzLjV2MTRjMCAxLjktNCAzLjUtOSAzLjVzLTktMS42LTktMy41eiIvPjxwYXRoIGQ9Ik0zIDExYzAgMS45IDQgMy41IDkgMy41czktMS42IDktMy41TTMgNS4yYzAgMS45IDQgMy41IDkgMy41czktMS42IDktMy41IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMjQxMEMiIHN0cm9rZS13aWR0aD0iMS42Ii8%2BPC9zdmc%2B)](https://www.trychroma.com) |
| Infrastructure | [![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik02LjUgMjBoMTEuNWE1IDUgMCAwIDAgLjktOS45MkE3IDcgMCAwIDAgNS41IDguNiA1Ljc1IDUuNzUgMCAwIDAgNi41IDIweiIvPjwvc3ZnPg%3D%3D)](https://aws.amazon.com) [![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com) [![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org) |
