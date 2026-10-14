<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:05051A,25:15104A,50:3A176D,75:007F89,100:00F5D4&height=230&section=header&text=Babar%20Khan%20Durrani&fontSize=46&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=AI%20%2F%20Computer%20Vision%20%2F%20Robotics&descAlignY=60&descSize=18&descColor=00F5D4" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=700&color=00F5D4&center=true&vCenter=true&repeat=true&width=850&height=35&lines=Building+AI+that+sees%2C+reasons+and+ships;RoboSight+%E2%80%A2+VisionServe+%E2%80%A2+RAG+%E2%80%A2+Computer+Vision;Final-year+Robotics+%26+Intelligent+Systems+%40+Bahria+University"/>

<br/>

<a href="https://babarkhand.github.io/">
<img src="https://img.shields.io/badge/%F0%9F%8C%90%20VIEW%20MY%20PORTFOLIO-babarkhand.github.io-00F5D4?style=for-the-badge&labelColor=090B20"/>
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/babar-khan-durrani-542a98277"><img src="https://img.shields.io/badge/LinkedIn-00A8FF?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=090B20"/></a>
<a href="mailto:kdurranibabar@gmail.com"><img src="https://img.shields.io/badge/Gmail-F72585?style=for-the-badge&logo=gmail&logoColor=white&labelColor=090B20"/></a>
<a href="https://contra.com/babar_durrani_3fgf7tlz/work?r=babar_durrani_3fgf7tlz"><img src="https://img.shields.io/badge/Contra-7B2CFF?style=for-the-badge&logoColor=white&labelColor=090B20"/></a>

<br/><br/>

`✦ COMPUTER VISION ✦ GENERATIVE AI / RAG ✦ AI ENGINEERING ✦ ROBOTICS ✦`

</div>

---

## 👋 10-second tour

| | |
|---|---|
| 🎓 **Studying** | BS Robotics & Intelligent Systems, Bahria University (CGPA 3.11) |
| 🤖 **Did** | AI & ML Intern at Embotics: offline RAG for an AI Teacher Robot on Raspberry Pi |
| 🔭 **Building** | Perception, inference serving and local LLM systems |
| 🤝 **Open to** | Internships and junior roles in AI/ML, computer vision and robotics |
| 🗣️ **Languages** | Pashto · Urdu · English · Punjabi |

---

## 🚀 Flagship systems

### 👁️ [RoboSight](https://github.com/BabarKhanD/robosight): robotic visual perception, software only

```mermaid
flowchart LR
  A[📷 RGB image / video] --> B[YOLOv8-Seg]
  B --> C[Depth Anything V2]
  C --> D[ByteTrack]
  D --> E[2.5D scene graph]
  E --> F[🤖 Robot queries]
```

Turns a single camera image into a spatial scene graph and answers questions like *"which object is closest?"* with a rules-based query layer. Runs on CPU, no hardware needed.

### ⚡ [VisionServe](https://github.com/BabarKhanD/visionserve): production CV inference platform

```mermaid
flowchart LR
  A[Client upload] --> B[FastAPI]
  B --> C{PyTorch or ONNX Runtime}
  C --> D[(PostgreSQL)]
```

| Backend | Mean latency (CPU) | FPS | RAM |
|---|---|---|---|
| PyTorch | 195.9 ms | 5.09 | 300 MB |
| **ONNX Runtime** | **137.2 ms** | **7.31** | **142 MB** |

**1.43× faster**, 73 passing tests, Docker Compose deployment, model versioning, structured logging.
`FastAPI` `PostgreSQL` `Docker` `PyTorch` `ONNX Runtime`

---

## 🧪 More projects

<table>
<tr>
<td width="50%" valign="top">

### 🩻 [Bone Metastasis Detection](https://github.com/BabarKhanD/bone-scan-metastasis-detection)
Dual-view CNN on nuclear medicine bone scans with Grad-CAM. **Focal Loss CNN caught 15/15** metastasis cases (baseline CNN 8/15, ViT 4/15).
`PyTorch` `Focal Loss` `Grad-CAM`

</td>
<td width="50%" valign="top">

### 🔍 [Visual Anomaly Inspection](https://github.com/BabarKhanD/visual-anomaly-inspection)
Unsupervised defect detection with ResNet-50 features. **0.847 ROC-AUC, 0.969 AP** on MVTec AD 2 Sheet Metal.
`PyTorch` `OpenCV` `Scikit-learn`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚽ [Football AI Tactical Analysis](https://github.com/BabarKhanD/football-ai-tactical-analysis)
Custom YOLO detection, team classification, possession analysis and player activity recognition from match video.
`YOLO` `ByteTrack` `K-Means`

</td>
<td width="50%" valign="top">

### 🧠 [Local AI Research Assistant](https://github.com/BabarKhanD/local-ai-research-assistant)
100% local RAG for paper Q&A, summaries and comparison. BGE + ChromaDB + Gemma 3 via LM Studio.
`RAG` `ChromaDB` `Local LLMs`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏎️ [F1 Track Limits](https://github.com/BabarKhanD/f1-track-limits-ambiguous-classification)
Classifier for the ambiguous "no advantage" cases. **F1-macro 0.887, ROC-AUC 0.942** over 4,254 incidents.
`FastF1` `Random Forest` `SHAP`

</td>
<td width="50%" valign="top">

### 📄 [Resume Analyzer](https://github.com/BabarKhanD/resume-analyzer)
Offline ATS scoring and skill-gap feedback against 30 job roles using sentence embeddings.
`Sentence Transformers` `PyMuPDF`

</td>
</tr>
</table>

<div align="center">

[🌊 AUV sensor selection](https://github.com/BabarKhanD/adaptive-sensor-selection-auv-navigation) · [🏠 Property doc intelligence](https://github.com/BabarKhanD/property-doc-intelligence) · [🛠️ Maintenance AI](https://github.com/BabarKhanD/maintenance-ai) · [❤️ Heart disease ML](https://github.com/BabarKhanD/heart-disease-prediction-ml) · [📈 Apple stock ML](https://github.com/BabarKhanD/stock_price_apple) · [🏡 House price ML](https://github.com/BabarKhanD/House-Price-Prediction-)

</div>

---

## 🧰 Loadout

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,pytorch,sklearn,opencv,fastapi,postgres,docker,git,raspberrypi,arduino,matlab&theme=dark"/>

`YOLO` `ONNX Runtime` `ByteTrack` `RAG` `Ollama` `ChromaDB` `Sentence Transformers` `n8n` `ESP32` `Proteus` `Cisco Packet Tracer`

</div>

---

## 💼 Experience

<details open>
<summary><b>🤖 AI & ML Intern · Embotics (Pvt.) Ltd.</b> · Jul 2026 – Sep 2026</summary>

- Offline RAG pipeline for an AI Teacher Robot: OCR, cleaning, chunking, BGE embeddings, FAISS index (111 chunks)
- Local LLM answers through Ollama (qwen2.5), compared RAG vs No-RAG on a 50-question test set
- Deployed and tested on Raspberry Pi, with audio-based interaction
</details>

<details>
<summary><b>🧠 AI/ML Engineering Intern · DevelopersHub</b> · Jul – Aug 2025 · Best Award certificate</summary>

- Built and evaluated ML models on structured data: EDA, preprocessing, validation, clean documented code
</details>

<details>
<summary><b>🎯 Leadership · IEEE, Bahria University</b> · 2024 – 2026</summary>

- Deputy Director (Technical): planned the IEEE E-Hunt competition · Deputy Director (Sports): IEEE RAS
</details>

<details>
<summary><b>☎️ Earlier roles</b> · 2023</summary>

- Customer Service Representative, Bridgeway Telecom (UK B2B sales) · Appointment Setter, EDM Solutions
</details>

---

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=BabarKhanD&show_icons=true&theme=tokyonight&hide_border=true&bg_color=090B20&title_color=00F5D4&icon_color=F72585&text_color=E6EDF3"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BabarKhanD&layout=compact&theme=tokyonight&hide_border=true&bg_color=090B20&title_color=00F5D4&text_color=E6EDF3"/>

</div>

---

<div align="center">

### 📫 Let's build something

I'm up for conversations about computer vision, RAG systems and robotics.

<a href="https://babarkhand.github.io/"><img src="https://img.shields.io/badge/Portfolio-00F5D4?style=for-the-badge&labelColor=090B20"/></a>
<a href="mailto:kdurranibabar@gmail.com"><img src="https://img.shields.io/badge/Email_me-F72585?style=for-the-badge&logo=gmail&logoColor=white&labelColor=090B20"/></a>

<img src="https://komarev.com/ghpvc/?username=BabarKhanD&label=PROFILE%20VIEWS&color=00F5D4&style=for-the-badge&labelColor=090B20"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5D4,30:007F89,60:3A176D,100:05051A&height=120&section=footer" width="100%"/>

</div>
