<div align="center">

# Ganesh Pavan Kartikeya Bharadhwaj Kolluri (Karthik Kolluri)

**PhD Researcher, University of Essex · AI Engineer (NLP), Hivedome Ltd.**<br>
Compression, distillation, and fairness in speech and audio language models<br>
<sub>Ganesh Pavan Kartikeya Bharadwaj Kolluri (G. P. K. B. Kolluri)</sub>

[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=mIv1JY0AAAAJ&hl=en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D)](https://www.linkedin.com/in/karthik-bharadhwaj-1998kb/)
[![Semantic Scholar](https://img.shields.io/badge/Semantic_Scholar-1857B6?style=for-the-badge&logo=semanticscholar&logoColor=white)](https://www.semanticscholar.org/author/Ganesh-Pavan-Kartikeya-Bharadwaj-Kolluri/2426796570)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-8549-4474)
[![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/KarthikKB1998)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:karthikbharadhwaj1998@gmail.com)

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
[arXiv](https://arxiv.org/abs/2609.38106) · [Code](https://github.com/karthikbharadhwajKB/SpeechLLM-Pruning-Fairness)

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
  <a href="https://www.python.org"><img src="https://skillicons.dev/icons?i=python&theme=dark" width="44" alt="Python" /></a>
  <a href="https://pytorch.org"><img src="https://skillicons.dev/icons?i=pytorch&theme=dark" width="44" alt="PyTorch" /></a>
  <a href="https://www.tensorflow.org"><img src="https://skillicons.dev/icons?i=tensorflow&theme=dark" width="44" alt="TensorFlow" /></a>
  <a href="https://scikit-learn.org"><img src="https://skillicons.dev/icons?i=sklearn&theme=dark" width="44" alt="scikit-learn" /></a>
  <a href="https://dart.dev"><img src="https://skillicons.dev/icons?i=dart&theme=dark" width="44" alt="Dart" /></a>
  <a href="https://flutter.dev"><img src="https://skillicons.dev/icons?i=flutter&theme=dark" width="44" alt="Flutter" /></a>
  <a href="https://www.gnu.org/software/bash/"><img src="https://skillicons.dev/icons?i=bash&theme=dark" width="44" alt="Bash" /></a>
  <a href="https://www.kernel.org"><img src="https://skillicons.dev/icons?i=linux&theme=dark" width="44" alt="Linux" /></a>
  <a href="https://git-scm.com"><img src="https://skillicons.dev/icons?i=git&theme=dark" width="44" alt="Git" /></a>
  <a href="https://github.com"><img src="https://skillicons.dev/icons?i=github&theme=dark" width="44" alt="GitHub" /></a>
  <a href="https://aws.amazon.com"><img src="https://skillicons.dev/icons?i=aws&theme=dark" width="44" alt="AWS" /></a>
  <a href="https://www.latex-project.org"><img src="https://skillicons.dev/icons?i=latex&theme=dark" width="44" alt="LaTeX" /></a>
</p>

| Area | Tools |
| :--- | :--- |
| Languages | [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org) [![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)](https://dart.dev) [![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/) [![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org) |
| Deep learning | [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org) [![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/docs/transformers) [![PEFT / LoRA](https://img.shields.io/badge/PEFT_%2F_LoRA-FF9D00?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/docs/peft) [![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://www.tensorflow.org) [![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)](https://keras.io) [![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org) |
| Speech and audio | [![Whisper](https://img.shields.io/badge/Whisper-10A37F?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjEiIHk9IjkiIHdpZHRoPSIyLjQiIGhlaWdodD0iNiIgcng9IjEuMiIvPjxyZWN0IHg9IjUuNCIgeT0iNSIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIxNCIgcng9IjEuMiIvPjxyZWN0IHg9IjkuOCIgeT0iMiIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIyMCIgcng9IjEuMiIvPjxyZWN0IHg9IjE0LjIiIHk9IjYiIHdpZHRoPSIyLjQiIGhlaWdodD0iMTIiIHJ4PSIxLjIiLz48cmVjdCB4PSIxOC42IiB5PSI5IiB3aWR0aD0iMi40IiBoZWlnaHQ9IjYiIHJ4PSIxLjIiLz48L3N2Zz4%3D)](https://github.com/openai/whisper) [![SLAM-ASR](https://img.shields.io/badge/SLAM--ASR-7C3AED?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxyZWN0IHg9IjEiIHk9IjkiIHdpZHRoPSIyLjQiIGhlaWdodD0iNiIgcng9IjEuMiIvPjxyZWN0IHg9IjUuNCIgeT0iNSIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIxNCIgcng9IjEuMiIvPjxyZWN0IHg9IjkuOCIgeT0iMiIgd2lkdGg9IjIuNCIgaGVpZ2h0PSIyMCIgcng9IjEuMiIvPjxyZWN0IHg9IjE0LjIiIHk9IjYiIHdpZHRoPSIyLjQiIGhlaWdodD0iMTIiIHJ4PSIxLjIiLz48cmVjdCB4PSIxOC42IiB5PSI5IiB3aWR0aD0iMi40IiBoZWlnaHQ9IjYiIHJ4PSIxLjIiLz48L3N2Zz4%3D)](https://github.com/X-LANCE/SLAM-LLM) [![Common Voice](https://img.shields.io/badge/Common_Voice-0060DF?style=flat-square&logo=mozilla&logoColor=white)](https://commonvoice.mozilla.org) |
| LLMs and agents | [![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)](https://www.langchain.com) [![OpenAI Agents SDK](https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMTEiIHk9IjEuNSIgd2lkdGg9IjIiIGhlaWdodD0iNSIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjIuNSIgcj0iMS44IiBmaWxsPSJ3aGl0ZSIvPjxyZWN0IHg9IjMiIHk9IjYuNSIgd2lkdGg9IjE4IiBoZWlnaHQ9IjE0IiByeD0iNCIgZmlsbD0id2hpdGUiLz48Y2lyY2xlIGN4PSI4LjUiIGN5PSIxMyIgcj0iMiIgZmlsbD0iIzQxMjk5MSIvPjxjaXJjbGUgY3g9IjE1LjUiIGN5PSIxMyIgcj0iMiIgZmlsbD0iIzQxMjk5MSIvPjwvc3ZnPg%3D%3D)](https://openai.github.io/openai-agents-python/) [![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat-square&logo=modelcontextprotocol&logoColor=white)](https://modelcontextprotocol.io) [![Ollama](https://img.shields.io/badge/Ollama-4B5563?style=flat-square&logo=ollama&logoColor=white)](https://ollama.com) [![Unsloth](https://img.shields.io/badge/Unsloth-0E9F6E?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMy41IDEuNUwzLjUgMTRoN2wtMS41IDguNUwyMC41IDkuNWgtN3oiLz48L3N2Zz4%3D)](https://unsloth.ai) [![TRL](https://img.shields.io/badge/TRL-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/docs/trl) [![RAG](https://img.shields.io/badge/RAG-2F81F7?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGNpcmNsZSBjeD0iMTAiIGN5PSIxMCIgcj0iNi41IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIuOCIvPjxwYXRoIGQ9Ik0xNSAxNWw2LjUgNi41IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjMiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPjwvc3ZnPg%3D%3D)](https://arxiv.org/abs/2005.11401) |
| Retrieval | [![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white)](https://opensearch.org) [![Chroma](https://img.shields.io/badge/Chroma-F97316?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0zIDVjMC0xLjkgNC0zLjUgOS0zLjVzOSAxLjYgOSAzLjV2MTRjMCAxLjktNCAzLjUtOSAzLjVzLTktMS42LTktMy41eiIvPjxwYXRoIGQ9Ik0zIDExYzAgMS45IDQgMy41IDkgMy41czktMS42IDktMy41TTMgNS4yYzAgMS45IDQgMy41IDkgMy41czktMS42IDktMy41IiBmaWxsPSJub25lIiBzdHJva2U9IiNDMjQxMEMiIHN0cm9rZS13aWR0aD0iMS42Ii8%2BPC9zdmc%2B)](https://www.trychroma.com) [![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)](https://github.com/facebookresearch/faiss) |
| Infrastructure and tools | [![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik02LjUgMjBoMTEuNWE1IDUgMCAwIDAgLjktOS45MkE3IDcgMCAwIDAgNS41IDguNiA1Ljc1IDUuNzUgMCAwIDAgNi41IDIweiIvPjwvc3ZnPg%3D%3D)](https://aws.amazon.com) [![Weights & Biases](https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)](https://wandb.ai) [![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square&logo=uv&logoColor=white)](https://docs.astral.sh/uv/) [![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com) [![GitHub](https://img.shields.io/badge/GitHub-4B5563?style=flat-square&logo=github&logoColor=white)](https://github.com) [![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org) [![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io) [![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev) [![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org) |
