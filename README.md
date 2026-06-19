<div align="center">

# Hey, I'm Sriram R 👋

**Machine Learning Researcher · Full-Stack Developer · Builder**

*I work at the boundary of ML research and real products —
from self-supervised vision models trained on medical imaging
to full-stack platforms used by real students.*

[![Email](https://img.shields.io/badge/Email-sram36505@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sram36505@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-sriram36505-181717?style=flat&logo=github)](https://github.com/sriram36505)

</div>

---

## What I'm building

### 🧠 VL-JEPA — Medical VQA for Spine Imaging *(IIT Kanpur)*
Pretrained a vision encoder **from scratch** using the self-supervised i-JEPA objective
on 50,498 spine X-ray and MRI images. Built a novel embedding-prediction VQA model
that retrieves answers by cosine similarity in latent space rather than fixed class weights.

- **77.72 ± 0.32% macro accuracy** across 8 question types on a 12,498-sample test set
- **60.4% Severe stenosis recall** — the rare but clinically critical class (~3.7% of data)
- +9.3 pts over the cross-entropy baseline on severity grading, where it matters most
- Splits verified leak-free at the image level across 50K+ training images

→ [View repo & full results](https://github.com/sriram36505/VL-JEPA)

---

### 🛒 Campus Marketplace
A verified-student buy/sell platform — any college, zero fees, trust by design.

Students sign in with their institutional email. Campus isolation is enforced at the
**database layer via Row-Level Security**, not in app code. One codebase, every
college gets its own scoped marketplace.

- AI snap-to-list: photograph an item, a vision model writes the listing
- Semantic search via pgvector — finds items by meaning, not just keywords
- Real-time buyer↔seller chat with Supabase Realtime
- Provider-agnostic AI layer: swap between self-hosted GPU and cloud with one env var

→ [View repo](https://github.com/sriram36505/campus-marketplace)

---

### 🌶️ VisionSpice
Fine-grained Indian spice classification across 19 classes under real-world conditions.

- **96.8% test accuracy · macro-F1: 0.967** on 10,991 images
- EfficientNet-B3 + custom stage-level SE attention
- +12.9pp over scratch baseline · 19ms inference · 12.5M parameters

→ [View repo](https://github.com/sriram36505/VisionSpice)

---

### 🚗 HSTA-YOLO — Nighttime Vehicle Detection
Four-stage pipeline for nighttime detection tackling glare, motion blur, and noise.

- **mAP@50: 0.975 · F1: 0.956 · 40 FPS** on NVIDIA T4
- **+8.7 points** over Gold-YOLO baseline
- CLAHE preprocessing alone contributes more than all learned attention combined (+43.7% mAP@95)

→ [View repo](https://github.com/sriram36505/noctiloc-models)

---

## What I care about

- Self-supervised learning and representation quality over supervised shortcuts
- Models that work on rare classes, not just easy majorities
- Systems where security and correctness are structural — not bolted on
- AI features that degrade gracefully (fallbacks, not hard failures)
- Building things that real people actually use

---

## Tech

**ML / CV / Research**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Full-Stack**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Other**

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Project index

| Project | What it is | Stack |
|---|---|---|
| [VL-JEPA](https://github.com/sriram36505/VL-JEPA) | Self-supervised spine VQA — 77.72% macro acc, 60.4% Severe recall | PyTorch, BioBERT, i-JEPA |
| [campus-marketplace](https://github.com/sriram36505/campus-marketplace) | Verified-student marketplace with AI and real-time chat | Next.js, Supabase, pgvector |
| [VisionSpice](https://github.com/sriram36505/VisionSpice) | Indian spice classification with transfer learning | PyTorch, EfficientNet-B0 |
| [noctiloc-models](https://github.com/sriram36505/noctiloc-models) | Nighttime vehicle detection with temporal attention | YOLOv8, ConvLSTM |
| [Ai-smart-home-automation](https://github.com/sriram36505/Ai-smart-home-automation-) | AI-driven home automation system | C++ |

---

<div align="center">

*Open to research collaborations and internships in ML, computer vision, and full-stack engineering.*

📬 [sram36505@gmail.com](mailto:sram36505@gmail.com)

</div>
