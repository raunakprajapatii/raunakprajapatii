<div align="center">

# Hey, I'm Rounak Prajapati 👋

**CS undergrad at IIITDM Jabalpur** · Full-Stack Dev · LLM/RAG Engineering · Computer Vision enthusiast

[![Email](https://img.shields.io/badge/Email-rounakprajapati7%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rounakprajapati7@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rounak%20Prajapati-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rounak-prajapati-3896jee)

</div>

---

## About Me

- 🎓 **B.Tech CSE** @ IIITDM Jabalpur (Batch 2024–2028) · CPI: **8.5** (till Sem IV)
- 🔭 Currently building on full-stack + deep learning foundations through structured coursework in **RAG and LLM engineering**
- 🤝 Open to internships, open-source contributions, and collaborations
- 🎾 Active lawn tennis club member; also love music and drawing

---

## 🛠️ Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Web & Databases**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**LLM / GenAI Engineering**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E1E1E?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

*RAG · QLoRA Fine-Tuning · Prompt Engineering · Vector Embeddings*

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

*timm · torchvision · Vision Transformers (ViT) · Mixed Precision (FP16/AMP) · Transfer Learning*

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 🚀 Featured Projects

### 🔍 Creatine RAG Assistant — Grounded, Citation-Verified Research Assistant
> Multi-layer RAG pipeline over 423 curated PubMed Central articles with hallucination-checking and confidence-based abstention

- ChromaDB vector store with S-PubMedBert embeddings for topic-routed retrieval and paper ranking
- Extracts numeric facts (dosages, sample sizes, percentages) and verifies each appears verbatim in its source chunk
- Cross-checks every generated citation against retrieved chunks to flag possible hallucinations
- Pre-LLM relevance threshold so the system explicitly abstains under low retrieval confidence instead of guessing
- FastAPI backend + React frontend with a retrieval-trace panel

`Python` `FastAPI` `ChromaDB` `SentenceTransformers` `Groq LLM` `React`

---

### 🐍 SerpentAI — Indian Snake Species Classifier
> Fine-tuned **DINOv2 ViT-L/14** on 13K+ SnakeCLEF 2022 images to build a 49-class classifier — **94.8% validation accuracy (98.4% top-5)**

- 49 classes: 48 Indian snake species + a self-curated "no-snake" distractor class
- Two-phase, 30-epoch training: backbone frozen for 7 epochs (head warm-up) → fully unfrozen with cosine-annealed LR
- Mixed precision (FP16/AMP) training with gradient clipping, checkpoint-based resume support
- Multi-GPU (2×) training via DataParallel

`Python` `PyTorch` `timm` `DINOv2` `scikit-learn` `FP16/AMP` `Kaggle`

---

### ⚡ ProdHack — AI-Powered Productivity Tool
> Gamifies study sessions with AI-generated quiz challenges powered by **Gemini API** · Runner-up, "Can You Hack It" hackathon (Productive Track)

- User signup/login, profile dashboard, real-time 1v1 productivity battle rooms
- PDF upload and AI quiz generation
- Store items, wallet, theme equip flow, and playlist slots
- Leaderboard based on player progress
- CORS-ready deployment config for Vercel + Render

`React` `Express.js` `MongoDB` `Gemini API`

---

### 🌍 WanderWise — Travel Planning Web App
> Full-stack travel planner with 100+ destination records and full CRUD operations

- RESTful API backend with modular Express.js routing and middleware
- Responsive React frontend optimized for mobile and desktop
- Clean, scalable architecture built for extensibility

`React` `Express.js` `Node.js` `MySQL` `REST APIs`

---

## 🏆 Achievements

- 🥈 Runner-up, Productive Track — *"Can You Hack It"* (intra-college 24-hour hackathon), for ProdHack
- 🎯 Semifinalist, Flipkart Grid 8.0
- 📜 AI Engineer Core Track: LLM Engineering, RAG, QLoRA & Agents — Ligency/Ed Donner (Udemy)
- 📜 Programming with JavaScript — Meta (Coursera)
- 📜 HTML & CSS in Depth — Meta (Coursera)

---

## 📈 GitHub Stats

<div align="center">

![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=raunakprajapatii&theme=tokyonight)

![](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=raunakprajapatii&theme=tokyonight)

![](https://github-readme-activity-graph.vercel.app/graph?username=raunakprajapatii&theme=tokyo-night)

![](https://github-profile-trophy.vercel.app/?username=raunakprajapatii&theme=tokyonight&no-frame=true&margin-w=15)
</div>

---

<div align="center">
  <i>Open to internship opportunities in Full-Stack Development, ML, and LLM/RAG Engineering.</i><br/>
  <b>Let's build something meaningful together.</b>
</div>
