
<!-- GitHub Profile README | github.com/bavuong2005 -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:6C63FF&height=235&section=header&text=MAI%20LE%20BA%20VUONG&fontSize=42&fontColor=FFFFFF&animation=twinkling&fontAlignY=38&desc=COMPUTER%20SCIENCE%20%7C%20AI%20ENGINEERING&descAlignY=58&descSize=18"
    width="100%"
    alt="Mai Le Ba Vuong - AI Engineering"
  />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img
      src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=25&duration=2600&pause=900&color=9D4EDD&center=true&vCenter=true&width=850&height=65&lines=%E2%9A%A1+Aspiring+AI+Engineer;%F0%9F%A7%A0+LLM+%26+Agentic+AI;%F0%9F%91%81+Computer+Vision+%26+Deep+Learning;%F0%9F%9A%80+Building+Practical+AI+Systems"
      alt="Typing animation"
    />
  </a>
</p>

<p align="center">
  <a href="https://github.com/bavuong2005?tab=repositories">
    <img src="https://img.shields.io/badge/Explore_My_Projects-6C63FF?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/bavuong2005/legal-agentic-rag">
    <img src="https://img.shields.io/badge/Agentic_RAG-161B22?style=for-the-badge&logo=python&logoColor=white" />
  </a>
  <a href="https://github.com/bavuong2005/occlusion-aware-viton">
    <img src="https://img.shields.io/badge/Computer_Vision-161B22?style=for-the-badge&logo=pytorch&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 About Me

I'm a **Computer Science graduate** from the **University of Information Technology (UIT), VNU-HCM**, interested in building AI systems that solve real-world problems.

- 🧠 **LLM & Agentic AI:** Built legal QA systems using hybrid retrieval, reranking, LangGraph, selective reflection, and query rewriting.
- 👁️ **Computer Vision:** Worked with diffusion models, object detection, image segmentation, and virtual try-on.
- 🚗 **Currently exploring:** Scenario mining and simulation for autonomous driving applications.
- 🌱 **Learning:** Cloud computing, MLOps, and deploying AI applications reliably.

---

## 🛠️ Tech Stack & Tools

**AI & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**LLM, RAG & Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-20232A?style=for-the-badge&logo=langchain&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00A98F?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge)

**Development & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 🚀 Featured Projects

### ⚖️ RoadLaw — Agentic RAG for Vietnamese Traffic Law

**[Explore Repository](https://github.com/bavuong2005/legal-agentic-rag)**

An AI assistant for answering questions about Vietnamese traffic regulations, built on a **LangGraph agent** and a hybrid retrieval pipeline.

- **Retrieval:** Vietnamese BM25 + `gte-multilingual-base` embeddings, followed by BGE cross-encoder reranking.
- **Agentic workflow:** Tool calling, clarification requests, selective reflection, query rewriting, and multi-turn memory.
- **Evaluation:** **20/20 capability checks passed** in the project's 20-question evaluation across rewriting, clarification, memory, reasoning, and refusal scenarios.
- **Stack:** Python, LangGraph, Gemini, Weaviate, LangSmith, Streamlit.

<p align="center">
  <a href="https://github.com/bavuong2005/legal-agentic-rag">
    <img src="https://raw.githubusercontent.com/bavuong2005/legal-agentic-rag/main/demo.gif" alt="RoadLaw Agentic RAG demo" width="85%" />
  </a>
</p>

### 👕 Occlusion-Aware Virtual Try-On

**[Explore Repository](https://github.com/bavuong2005/occlusion-aware-viton)**

An extension of **StableVITON** that improves virtual try-on results when people are partially occluded by objects such as bags, arms, or hair.

- **Perception:** Grounding DINO, SAM, and SegFormer identify clothing regions and occluding objects.
- **Generation & restoration:** StableVITON generates the try-on result; mask-based alpha blending restores foreground details.
- **Engineering:** Staged model execution for managing limited GPU memory.
- **Stack:** Python, PyTorch, StableVITON, Grounding DINO, SAM, SegFormer.

**Visual Comparison**

| Ground Truth | StableVITON Baseline | Occlusion-Aware (Ours) |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/bavuong2005/occlusion-aware-viton/main/results/ground_truth_00.png" width="230" alt="Ground truth example" /> | <img src="https://raw.githubusercontent.com/bavuong2005/occlusion-aware-viton/main/results/upper_test_00_baseline.png" width="230" alt="StableVITON baseline example" /> | <img src="https://raw.githubusercontent.com/bavuong2005/occlusion-aware-viton/main/results/upper_test_00.png" width="230" alt="Occlusion-aware output example" /> |

**Evaluation against StableVITON**

| Metric | Baseline | Ours |
|:---|---:|---:|
| PSNR ↑ | 32.925 | **33.385** |
| LPIPS ↓ | 0.211 | **0.185** |
| FID ↓ | 152.830 | **105.558** |
| KID ↓ | 0.023 | **0.002** |

<sub>Results reported in the project repository; higher PSNR and lower LPIPS/FID/KID are better.</sub>

---

## 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bavuong2005&show_icons=true&theme=tokyonight&hide_border=true" height="165" alt="GitHub statistics" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bavuong2005&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Most used languages across GitHub repositories" />
</p>

---

## 📫 Connect

<p align="center">
  <a href="https://github.com/bavuong2005">
    <img src="https://img.shields.io/badge/GitHub-bavuong2005-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile" />
  </a>
</p>

<p align="center"><i>Always learning. Always building. 🚀</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:6C63FF&height=105&section=footer" width="100%" alt="Footer decoration" />
</p>
