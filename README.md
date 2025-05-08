## 🧠 GPT-4o for Image Restoration

### Systematic Evaluation of GPT-4o's Visual Capabilities in Real-World Image Restoration Tasks

### 👥 Authors  
**Hao Yang<sup>1</sup>**, **Yan Yang<sup>2</sup>**, **Ruikun Zhang<sup>1</sup>**, **Liyuan Pan<sup>1</sup>**  
<sup>1</sup>Beijing Institute of Technology, <sup>2</sup>Australian National University  
📧 Contact: hao.yang@bit.edu.cn  

---

### 📜 Abstract

OpenAI's GPT-4o model, integrating multi-modal inputs and outputs within an autoregressive architecture, has demonstrated unprecedented performance in image generation. In this work, we investigate its potential impact on the image restoration community. We present the first systematic evaluation of GPT-4o across diverse restoration tasks.

Our experiments reveal that, although restoration outputs from GPT-4o are visually appealing, they often suffer from pixel-level structural fidelity when compared to ground-truth images. Common issues include variations in image proportions, shifts in object positions and quantities, and changes in viewpoint.

To address this, taking **image dehazing**, **deraining**, and **low-light enhancement** as representative case studies, we show that GPT-4o’s outputs can serve as powerful **visual priors**, substantially enhancing the performance of existing restoration networks. This study provides practical guidelines and a baseline framework to facilitate the integration of GPT-4o into future image restoration pipelines.

We hope the study on GPT-4o-based restoration will accelerate innovation in the broader field of image generation. To support further research, **we release GPT-4o-restored images from over 10 widely used image restoration datasets.**

---

## 🗂️ Dataset Downloads

To support reproducible research and further development, we provide GPT-4o-restored images for **over 10 widely used** image restoration datasets:

| Dataset Name         | Restoration Task        | GPT-4o Outputs      | Original Dataset |
|----------------------|-------------------------|---------------------|------------------|
| O-Haze | Image Dehazing        | [Download 🔗](#)     | [Source 🔗](??? |
| Rain800            | Image Deraining         | [Download 🔗](#)     | [Source 🔗](???) |
| LOL (Low-Light)      | Low-Light Enhancement   | [Download 🔗](#)     | [Source 🔗](???) |
| XXXX               | XXXX          | Comming soon    | [Source 🔗](XXX) |
| XXXX               | XXXX          | Comming soon    | [Source 🔗](XXX) |
| XXXX               | XXXX          | Comming soon    | [Source 🔗](XXX) |
| XXXX               | XXXX          | Comming soon    | [Source 🔗](XXX) |

> 🔍 *We will continue expanding the list with more datasets and tasks.*

---

## 🖼️ Cover Page (Markdown)

```markdown
# GPT-4o for Image Restoration
> Enhancing Vision Tasks via Multi-modal Generative Priors

![cover](assets/cover_gpt4o_restoration.jpg)

**Authors**: [Your Name], [Collaborators]  
**Affiliation**: [Your Lab or Institution]  
📅 **Release Date**: May 2025

🧠 This repository contains our evaluation of GPT-4o for image restoration tasks, dataset outputs, baseline framework, and visual priors.

📂 `datasets/` — GPT-4o outputs  
📊 `results/` — Evaluation metrics and plots  
🧪 `baseline/` — Code for baseline model integration  
