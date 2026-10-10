# Hi, I'm Shravan 👋

> Machine Learning Engineer · Production ML & Applied GenAI. I build AI that works in production, for everyone who relies on it.

## About Me

I'm a **Master of Data Science** candidate at the University of British Columbia (graduating June 2027). Before that, I spent nearly five years in software and ML engineering at **Bosch**, nearly three of them in ML roles, most recently as a **Senior ML Engineer**.

At Bosch I:
- Deployed autoencoder-based anomaly detection that shortened component validation cycles by **4 months**, with an estimated **€300K+** in annualized savings
- Built Databricks/PySpark pipelines over **80+ TB** of sensor telemetry, cutting per-partition processing time by **50%+**
- Built **Valfred**, a multi-agent GenAI data assistant that cut routine data lookups from 10–15 minutes to about **1–2 minutes** for ~30 beta users
- Led a TensorFlow → PyTorch migration that reduced training time by **48%**

Accessibility is personal for me: a deaf childhood friend was routinely left out of conversations, and that's why I work on sign language technology. Projects like [Project Euphonia](https://sites.research.google/euphonia/about/) and [Project Relate](https://sites.research.google/relate/) are the kind of work I want to do.

When I'm not building, I'm playing guitar or hunting for good 80s music.

🌐 **Portfolio:** [shravnchandr.github.io](https://shravnchandr.github.io/), with case studies, research and my résumé

---

## What I'm Building

### [ASL Guide](https://github.com/shravnchandr/ASL-App): Learn American Sign Language with AI
A full-stack ASL learning platform. *(The hosted demo is currently offline; the source is all here.)*

- **In-browser fingerspelling recognition**: a 36-class TensorFlow.js classifier on MediaPipe hand landmarks, **95.5% accuracy** on a held-out test set, under 100 ms per prediction
- **English → ASL translation**: a two-agent LangGraph workflow applying **11** documented ASL grammar rules (topicalization, wh-questions, negation, classifiers and more)
- **Practice that sticks**: 100 animated signs with SM-2 spaced-repetition scheduling
- **Cost-aware**: ~73% fewer input tokens per request through Gemini context caching, plus Redis and in-memory caching
- **PWA**: installable and mobile-friendly

Built with: FastAPI · React · TypeScript · TensorFlow.js · MediaPipe · LangGraph · Gemini API · PostgreSQL · Redis · Docker

### [Sign Language Recognition & Translation](https://github.com/shravnchandr/Sign-Language-Translation): Research, 2024–present
Signer-independent sign language recognition, with each stage informing the next:

- **2024: LandmarkConformer.** A multi-stream Conformer over hand, pose and face landmarks with an adversarial signer discriminator. **76.65% top-1** across 250 Google ASL Signs classes, on a split by signer (no validation signer appears in training).
- **2025: Graph-based recognition (ST-GCN).** A spatial-temporal graph network over 209 landmark joints. It underperformed the Conformer, which motivated the move to learned discrete tokens.
- **2026: Neural Sign Language Translator (in progress).** A factorized VQ-VAE + Conformer sequence-to-sequence model for sentence-level translation, with hybrid CTC/attention decoding.

---

## Featured Work

### [Dynamic Sign Language Translator](https://doi.org/10.1109/ICCAR55106.2022.9782661): IEEE ICCAR 2022
Peer-reviewed paper from my final-year capstone at PES University. On a noisy, self-collected dataset of 15 ASL phrases, MediaPipe hand landmarks with XGBoost reached **90%+ accuracy**, while every deep learning approach tested stayed below 36%.

### [Diabetic Retinopathy Classifier with XAI](https://github.com/shravnchandr/Diabetic-Retinopathy)
Xception-based classifier on retina (fundus) images, with a **96% Kappa score** against expert labels. Grad-CAM shows the regions behind each prediction, so a clinician can check it.

### [Explainable Propaganda Detection](https://github.com/shravnchandr/Propaganda-XAI)
RoBERTa models that detect persuasion techniques in text, using emotion signals learned from GoEmotions, with SHAP word-level explanations of each prediction.

---

## Tech Stack

**ML / DL**: PyTorch · TensorFlow · TensorFlow.js · Keras · Scikit-learn · Transformers · MediaPipe · OpenCV · XGBoost

**GenAI**: LangGraph · LangChain · Gemini API · RAG · Prompt Engineering · AI Agents · Vector DBs

**Data & MLOps**: Databricks · PySpark · MLflow · Azure ML · Pandas · Power BI

**Backend**: Python · FastAPI · Flask · SQL · PostgreSQL · Redis · Docker

**Frontend**: React · TypeScript · JavaScript · HTML/CSS

**Tools**: Git · Linux · Kubernetes (basic)

---

## Let's Connect

I'm looking for **ML Engineer or Data Scientist roles**, especially in production ML, applied GenAI or accessibility: part-time from **January 2027** (up to 24 h/week) and full-time from **July 2027**. Based in Vancouver, open to relocating within Canada or the US, or to remote work.

📧 [schandra.nyc@gmail.com](mailto:schandra.nyc@gmail.com)
💼 [LinkedIn](https://linkedin.com/in/shravnchandr)
🌐 [Portfolio](https://shravnchandr.github.io/)
