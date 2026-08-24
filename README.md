# Hey, I'm Yougal Attri 👋
### AI / ML Engineer — Generative AI & Computer Vision

> *"I don't just build models — I build systems that work in the real world."*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit-1A1A18?style=for-the-badge)](https://Yougal17.github.io/Yougal17/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yougal-attri/)
[![Email](https://img.shields.io/badge/Email-Say_Hello-FF5C00?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yougalattri17@gmail.com)

AI/ML engineer with **2+ years** shipping production AI systems. I fine-tune transformer models on satellite imagery (**SAM**, **SegFormer**) and build **RAG pipelines** that answer questions over large document corpora — with citations, not hallucinations.

📍 Gurgaon, India · 🎓 B.Tech (Hons.) CS, Data Science — Akal University · 📄 Published with CRC Press

---

## 🔦 Featured — RBI Circular Intelligence System

**Hybrid RAG pipeline over 317 RBI regulatory circulars** (2022–2024, ~2.75M words)
**[Live demo](https://rbi-circular-intelligence.vercel.app)** · **[Repo](https://github.com/Yougal17/rbi-rag)** · **[API docs](https://rbi-backend.koyeb.app/docs)**

| | | | |
|:--|:--|:--|:--|
| **0.96** | **0.91** | **4,368** | **4–9s** |
| Answer relevancy | Context precision | Indexed chunks | End-to-end latency |

- **Scraping** — custom Playwright scraper handling ASP.NET token filtering and Cloudflare-protected PDFs
- **Indexing** — hierarchical chunking (120-word child / 600-word parent) into a self-hosted on-prem **Qdrant** database
- **Retrieval** — 4 layers: dense vector search → BM25 over 9,747 terms → Reciprocal Rank Fusion → cross-encoder re-ranking
- **Generation** — Gemini 2.5 Flash with enforced source citations and hallucination guarding
- **Evaluation** — RAGAS across 30 questions in 12 regulatory categories

`Python` · `Qdrant` · `BM25` · `Playwright` · `Gemini 2.5` · `RAGAS`

---

## 🛠️ Stack

**Generative AI**
![LLMs](https://img.shields.io/badge/LLMs-534AB7?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-1A3FFF?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**ML & Computer Vision**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Deployment**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Full Stack**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

---

## 💼 Experience

| When | Role | Where |
|:--|:--|:--|
| Aug 2026 – Present | Executive, Network Operations | Spectra, Gurgaon |
| Jul 2025 – Jul 2026 | Fault Repair Service Engineer | Nextel Communications, Gurgaon |
| Jan – Apr 2025 | Full Stack Developer Intern (MERN) | Panacea Infosec, New Delhi |
| Jun – Dec 2024 | AI / ML Intern | Panacea Infosec, New Delhi |
| Jan – Jun 2024 | Data Science Intern | Sabudh Foundation, Mohali |

**Highlights** — fine-tuned SAM and SegFormer on geospatial satellite imagery for **~70% improvement over baseline** · engineered production PyTorch/TensorFlow/FastAPI training and inference pipelines · built a **95% accuracy** classification pipeline and cut analysis turnaround **~30%**

[Full details on the portfolio →](https://Yougal17.github.io/Yougal17/)

---

## 🚀 Other Projects

| Project | What it does | Stack |
|:--|:--|:--|
| **[Lead Response Assistant](https://github.com/Yougal17/Lead-Response-Assistant)** | Multi-step LLM workflow — structured extraction, deterministic gap detection, rule-based safety guard | `Llama 3.1` `Ollama` `Python` |
| **[Helmet Detection · SSD](https://github.com/Yougal17/Helmet-Detection-Using-Caffe)** | Two-class SSD detector for motorcycle helmet compliance across a 764-image annotated dataset | `Caffe` `OpenCV` `SSD` |
| **[Brain Haemorrhage Detection](https://github.com/Yougal17/Implementation-of-A-Hounsfield-value-based-approach-for-automatic-recognition-of-brain-haemorrhage-)** | Hounsfield Unit–based haemorrhage detection and staging from CT DICOM images | `pydicom` `scikit-learn` `NumPy` |

---

## 📄 Publication

**"Blockchain in Supply Chain Management Industry: A New Era in Manufacturing Industry"**
Book chapter in *Intelligent Manufacturing: Exploring AI, Blockchain, and Smart Technologies in Industry 4.0*
CRC Press (Taylor & Francis) · March 2025

---

## 📊 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yougal17&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yougal17&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

## 📬 Let's Connect

Open to **AI/ML engineering roles** — generative AI, computer vision, and production ML.

📧 [yougalattri17@gmail.com](mailto:yougalattri17@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/yougal-attri/) · 🌐 [Portfolio](https://Yougal17.github.io/Yougal17/) · 📱 +91 78074 03195

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yougal17&color=534AB7&style=flat-square&label=Profile+Views"/>
</p>
