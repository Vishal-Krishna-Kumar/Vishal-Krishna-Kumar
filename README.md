<div align="center">

<table width="100%">
<tr>
<td width="64%" valign="middle">
<p><sub>RECRUITER SIGNAL BRIEF · vishal-krishna-kumar</sub></p>
<h1>Vishal Krishna Kumar</h1>
<h2>Applied AI &amp; Software Engineer</h2>
<p>M.S. CS (Data Science) @ CityU Seattle '27 · RAG / LLM evaluation / AI agents · Open to 2027 SWE &amp; ML roles</p>
<p><strong>● Open to full-time SWE / ML / Data Science roles · July 2027 · anywhere in the US</strong></p>
<p><sub>Based in Seattle, Washington</sub></p>
<p><a href="https://github.com/vishal-krishna-kumar">GitHub</a> &nbsp;·&nbsp; <a href="https://vishalkrishna.dev">Website</a> &nbsp;·&nbsp; <a href="https://www.vishalkrishna.dev/blog">Blog</a> &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/vishal-krishna-kumar-65583a201/">LinkedIn</a> &nbsp;·&nbsp; <a href="mailto:vishalkrishnakkr@gmail.com">Email</a></p>
</td>
<td width="36%" valign="middle" align="center">
<img src="https://avatars.githubusercontent.com/u/240536141?u=33195e663413818f40d7c6311428979ab1168bd3&amp;v=4" width="180" alt="VishalKrishnaKumar GitHub avatar" />
</td>
</tr>
</table>
</div>

## 💼 Experience
**AI Engineer Intern — Hirello.ai** (Jul–Sep 2026)
- Built a resume-grounded **RAG autofill feature** end to end: Python/FastAPI back end, Vertex AI (Gemini) generation, Pinecone retrieval, SQLAlchemy/MySQL, Vue 3 front end.
- Contributed code to **5 of the platform's 10 AI agents** (Resume Optimizer, LinkedIn Labs, Outreach, Action Academy, Chat with Hiro).
- Fixed production defects (Resume Optimizer, silent-save), repaired Gmail/Outlook/Yahoo **OAuth 2.0** connections, fixed an IDOR issue, and added regression + cross-browser end-to-end tests.
- 7-person team, ten one-week sprints, engineering-lead code review on every change.

**Graduate Researcher — Applied ML & Intelligent Systems, City University of Seattle** (2025–present)
- Modular **RAG pipelines** (dense + sparse retrieval, chunking, graph reasoning) and **LLM evaluation** harnesses.
- Reproducible PyTorch experiment workflows.

**Graduate Teaching Assistant — Computer Networks, Illinois Institute of Technology** (Jan–May 2025)

---

## 🚀 Featured projects

<p align="center"><a href="https://github.com/Vishal-Krishna-Kumar/chunkaudit"><img src="https://raw.githubusercontent.com/Vishal-Krishna-Kumar/chunkaudit/main/docs/demo.gif" width="92%" alt="chunkaudit demo: a table of chunking strategies with answer split rate, recall and context size" /></a></p>

| Project | What it is | Stack |
|---|---|---|
| [chunkaudit](https://github.com/Vishal-Krishna-Kumar/chunkaudit) | Audits RAG chunking strategies: how often they split the answer across chunks, and whether retrieval still finds it. On 10,570 SQuAD questions, fixed 200-word chunks with no overlap split the answering sentence 14.1% of the time. Offline, no API keys, 69 tests, CI | Python, NumPy, GitHub Actions |
| [ragbench](https://github.com/Vishal-Krishna-Kumar/ragbench) | Retrieval benchmarking for RAG: BM25, TF-IDF and hybrid RRF implemented from scratch on an inverted index, IR metrics (graded nDCG, MRR, recall@k), measured on BEIR SciFact, FastAPI service, 34 tests, CI + Docker | Python, NumPy, FastAPI, Docker, GitHub Actions |
| [GraphAugmented-Intelligence (GAI)](https://github.com/Vishal-Krishna-Kumar/GraphAugmented-Intelligence_GAI) | Knowledge-graph RAG for biomedical question answering, using the KG-RAG framework from the UCSF Baranzini Lab; evaluated GPT-4 and Llama on BiomixQA. I added a script that scores the published results, with tests and CI | Python, LLMs, knowledge graphs, RAG |
| [RAG-Pipeline](https://github.com/Vishal-Krishna-Kumar/RAG-Pipeline) | My walkthrough of Daniel Bourke's simple-local-rag tutorial: a local RAG pipeline over a 1,200-page textbook (PyMuPDF, sentence-transformers, Gemma) | Python, embeddings, Jupyter |
| [AeroForge-TRIAD](https://github.com/Vishal-Krishna-Kumar/AeroForge-TRIAD) | Pre-registered CFD study of run-level conformal certificates for neural-surrogate gradients (SU2 adjoint pipeline, FNO + MLP ensembles) — in progress | Python, PyTorch, SU2 |
| [BraTS Attention U-Net](https://github.com/Vishal-Krishna-Kumar/BRaTS-attention-Tumor-Segmentation-UNet-) | 3D Attention U-Net for brain-tumor segmentation (BraTS 2019); team lead, **2nd place, Hack for Research 2025** | PyTorch, 3D medical imaging |
| [DeepFake-Detection-System](https://github.com/Vishal-Krishna-Kumar/DeepFake-Detection-System) | XceptionNet-based deepfake detection framework; published at TDEMAS 2023 | TensorFlow/Keras, OpenCV |
| [AlphaZero-Chess](https://github.com/Vishal-Krishna-Kumar/AlphaZero-Chess) | Self-play AlphaZero-style agent with MCTS; 81% win rate vs a rule-based baseline | PyTorch, CUDA, MCTS |
| [NLP sequence labeling](https://github.com/Vishal-Krishna-Kumar/nlp-sequence-labeling-autocorrection) · [Formality classification](https://github.com/Vishal-Krishna-Kumar/nlp_FormalityClassification) | HMM/Viterbi + RNN/LSTM tagging and spelling correction; BiLSTM/CNN/BERT/DeBERTa formality classifier (GYAFC) | PyTorch, Hugging Face |

📄 **Publication:** S. Ezra Vethamani, Kawin P., Rishi R., Vishal K. *"Deepfake Detection System: AI and Deep Learning Framework for Cyber Verification."* TDEMAS, 2023.

---

## ✍️ Writing
- [How often does chunking cut the answer in half?](https://www.vishalkrishna.dev/blog/chunking-cuts-the-answer) Nine chunking strategies audited on 10,570 questions.
- [From 216 ms to 0.22 ms per query: an inverted index in NumPy](https://www.vishalkrishna.dev/blog/inverted-index-in-numpy) Same rankings, nearly 1,000 times faster, indexing memory down from 4.1 GB to 123 MB.

More at [vishalkrishna.dev/blog](https://www.vishalkrishna.dev/blog).

---

## 🛠️ Skills
**Languages:** Python · Java · C++ · Go · TypeScript/JavaScript · SQL
**AI/ML:** PyTorch · TensorFlow/Keras · scikit-learn · Hugging Face · LangChain · LLMs · RAG · AI agents · LLM evaluation · pandas · NumPy
**Back end & data:** FastAPI · Node.js · GraphQL · REST · OAuth 2.0 · PostgreSQL · MySQL · MongoDB · DynamoDB · BigQuery · Pinecone · FAISS · Neo4j
**Front end:** React · Next.js · Vue 3 · HTML/CSS
**Cloud & tools:** AWS · GCP (Vertex AI) · Azure · Docker · Git · CI/CD (GitHub Actions) · Linux

🏅 Gemini Enterprise Agent Ready (Google) · Claude 101 (Anthropic Academy) · Dean's Scholar, CityU

---

---
## 📈 GitHub activity
<p align="center">
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://www.gitskins.com/api/section/stats?username=vishal-krishna-kumar&theme=github-dark&avatar=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F240536141%3Fu%3D33195e663413818f40d7c6311428979ab1168bd3%26v%3D4&v=recruiter-stats-1&mode=light" />
  <img src="https://www.gitskins.com/api/section/stats?username=vishal-krishna-kumar&theme=github-dark&avatar=https%3A%2F%2Favatars.githubusercontent.com%2Fu%2F240536141%3Fu%3D33195e663413818f40d7c6311428979ab1168bd3%26v%3D4&v=recruiter-stats-1&mode=dark" width="100%" alt="VishalKrishnaKumar GitHub proof metrics" />
</picture>
</p>
