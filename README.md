# Hey, I'm Yougal Attri 👋
### AI / ML Engineer · Generative AI & Computer Vision

> *"I don't just build models — I build systems that work in the real world."*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit_Now-1A1A18?style=for-the-badge)](https://Yougal17.github.io/Yougal17/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yougal-attri/)
[![Email](https://img.shields.io/badge/Email-Say_Hello-FF5C00?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yougalattri17@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-+91_78074_03195-00C170?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+917807403195)

---

## 🧠 Who Am I?

AI/ML engineer with **2+ years of professional experience** delivering production-ready AI systems across **computer vision** and **generative AI**.

On the vision side, I've fine-tuned transformer-based networks (**SAM**, **SegFormer**) for satellite image segmentation and built the end-to-end Python training and inference pipelines around them. On the GenAI side, I've built a production-grade **RAG system over 317 RBI regulatory circulars** — hybrid retrieval, cross-encoder re-ranking, and an LLM generation layer that cites its sources, scoring **0.96 answer relevancy** on RAGAS.

I'm a **B.Tech (Hons.) CS graduate** with a Data Science specialization from **Akal University, Bathinda**, and a published book chapter with **CRC Press (Taylor & Francis)**.

I care about **clean code**, **real-world impact**, and **shipping things that actually work**.

---

## 🚀 What I've Built

### 📑 RBI Circular Intelligence System — Hybrid RAG Pipeline
> A retrieval-augmented QA system over **317 RBI regulatory circulars** (2022–2024, ~2.75M words)

**[→ github.com/Yougal17/rbi-rag](https://github.com/Yougal17/rbi-rag)**

- Full pipeline in Python: scraping → parsing → chunking → retrieval → generation, with **every answer citing its source circular, date, and URL**
- Custom **Playwright** scraper handling ASP.NET token-based filtering and Cloudflare-protected PDF delivery
- Hierarchical chunking (120-word child / 600-word parent) → **4,368 chunks** indexed in a self-hosted on-prem **Qdrant** vector database
- **4-layer hybrid retrieval**: dense vector search + BM25 over a 9,747-term vocabulary + Reciprocal Rank Fusion + cross-encoder re-ranking
- **Gemini 2.5 Flash** generation layer with enforced citations and hallucination guarding
- Latency: **0.5–3.5s retrieval**, **4–9s end-to-end**
- Evaluated with **RAGAS** across 30 questions in 12 regulatory categories → **0.96 answer relevancy**, **0.91 context precision**, 0.775 overall
- Stack: `Python` `Qdrant` `BM25` `Playwright` `Gemini 2.5` `RAGAS`

---

### 🌍 Geospatial Image Segmentation using SAM (Meta AI)
> Fine-tuned **Segment Anything Model** for land-use classification & boundary detection

- Customized SAM with transfer learning + domain-specific data augmentation
- Achieved **~70% improvement over baseline** on geospatial segmentation tasks
- Stack: `PyTorch` `Python` `OpenCV` `FastAPI`

---

### 🛰️ Semantic Segmentation with SegFormer (Transformer Architecture)
> Multi-class segmentation pipeline for remote sensing image analysis

- Designed a full training pipeline using the SegFormer transformer architecture
- Custom **imbalanced-class loss functions** + hyperparameter tuning for edge cases
- Deployed on real-world satellite imagery datasets
- Stack: `TensorFlow` `Python` `SegFormer` `NumPy`

---

### 🍱 Food Product Classification System
> End-to-end ML pipeline — from raw data to predictions

- Built a **custom web scraper** to collect and label training data at scale
- Designed the full ML pipeline: preprocessing → feature engineering → model → deploy
- Hit **95% classification accuracy** — ready for market intelligence use cases
- Stack: `scikit-learn` `Pandas` `Python` `BeautifulSoup`

---

## 💼 Experience Timeline

```
📅 Aug 2026 – Present
   🔵 Executive, Network Operations — Spectra, Gurgaon
      ↳ Enterprise network operations

📅 Jul 2025 – Jul 2026
   🟠 Fault Repair Service Engineer — Nextel Communications, Gurgaon
      ↳ SLA-driven fault resolution · trend & failure-cause reporting

📅 Jan 2025 – Apr 2025
   🟢 Full Stack Developer Intern (MERN) — Panacea Infosec Pvt. Ltd., New Delhi
      ↳ Cybersecurity audit web app · React.js · Node.js · JWT Auth · MongoDB

📅 Jun 2024 – Dec 2024
   🩷 AI / ML Intern — Panacea Infosec Pvt. Ltd., New Delhi
      ↳ SAM + SegFormer fine-tuning · PyTorch · TensorFlow · FastAPI pipelines

📅 Jan 2024 – Jun 2024
   🟣 Data Science Intern — Sabudh Foundation, Mohali
      ↳ ML models for social impact · 95% accuracy pipeline · 30% faster workflows
```

---

## 🛠️ Tech Stack

### Generative AI
![LLMs](https://img.shields.io/badge/LLMs-534AB7?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-1A3FFF?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Embeddings](https://img.shields.io/badge/Embeddings-00C170?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-FF2D8A?style=flat-square)

### Machine Learning & Computer Vision
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Pipelines & Deployment
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### Full Stack
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

---

## 📄 Publication

**"Blockchain in Supply Chain Management Industry: A New Era in Manufacturing Industry"**
Book chapter in *Intelligent Manufacturing: Exploring AI, Blockchain, and Smart Technologies in Industry 4.0*
**CRC Press (Taylor & Francis)** · March 2025

---

## 🎓 Education

🏛️ **Bachelor of Technology (Hons.) — Computer Science & Engineering**
Specialization: **Data Science** · Akal University, Bathinda, Punjab
`2020 – 2024` · **CGPA: 8.36 / 10**

---

## 🏆 Leadership & Achievements

- 🥈 **2nd Place** — Start-up Pitch Competition at Akal University
- 🎙️ **Founder Member** — Turing Truncheons Student Tech Club
- 🎉 Led **Engineer's Day event** with **200+ attendees** as chief organizer

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yougal17&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yougal17&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

## 📬 Let's Connect

Open to **AI/ML engineering roles** — generative AI, computer vision, and production ML. If you're hiring, collaborating, or just want to talk tech, reach out.

| | |
|---|---|
| 📧 Email | [yougalattri17@gmail.com](mailto:yougalattri17@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/yougal-attri](https://www.linkedin.com/in/yougal-attri/) |
| 🐙 GitHub | [github.com/Yougal17](https://github.com/Yougal17) |
| 🌐 Portfolio | [View Portfolio →](https://Yougal17.github.io/Yougal17/) |
| 📱 Phone | +91 78074 03195 |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Yougal17&color=534AB7&style=flat-square&label=Profile+Views"/>
</p>

<p align="center"><i>Building AI systems that ship · Fast replies · Let's build something great.</i></p>
