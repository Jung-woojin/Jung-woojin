<div align="center">

# Woojin Jung · 정우진

### Computer Vision Researcher & AI Engineer

I study **robust visual perception** and build research systems that turn papers,
experiments, and failure cases into reproducible engineering decisions.

[![Computer Vision](https://img.shields.io/badge/Computer_Vision-0B5CAD?style=flat-square)](https://github.com/Jung-woojin?tab=repositories)
[![Object Detection](https://img.shields.io/badge/Object_Detection-7B2CBF?style=flat-square)](https://github.com/Jung-woojin/object-detection-notes)
[![Robust Vision](https://img.shields.io/badge/Robust_Vision-00796B?style=flat-square)](https://github.com/Jung-woojin/Sea-Fog-Classification-via-Kernel-Size-Scaling-Based-Effective-Receptive-Field-Expansion)
[![Research Automation](https://img.shields.io/badge/Research_Automation-C2410C?style=flat-square)](https://github.com/Jung-woojin/cv-research-radar)
[![Open to Collaboration](https://img.shields.io/badge/Open_to-Collaboration-1F883D?style=flat-square)](mailto:wojin010629@gmail.com)

</div>

---

## About me

My work connects **CNN architecture design, effective receptive fields, signal processing, object detection, and real-world deployment**. I am especially interested in models that remain useful when data is limited, domains shift, visibility degrades, or edge hardware constrains the design.

I organize my GitHub as a working research system:

```text
research question → evidence map → minimal experiment → failure analysis
                  → reproducible artifact → reusable knowledge
```

- **Research:** effective receptive field (ERF), large-kernel CNNs, robust perception, open-vocabulary detection, vision-language models
- **Application domains:** maritime CCTV, sea fog and low visibility, distance/depth estimation, real-time and edge vision
- **Engineering:** PyTorch experiments, ablation design, Grad-CAM/ERF analysis, benchmark tracking, automated research archives
- **Foundations:** convolution as a signal-processing operator, linear algebra for representation learning, optimization and frequency analysis

## What I am building now

### 1. Robust maritime vision through receptive-field design

[**Sea Fog Classification via Kernel Size Scaling-Based Effective Receptive Field Expansion**](https://github.com/Jung-woojin/Sea-Fog-Classification-via-Kernel-Size-Scaling-Based-Effective-Receptive-Field-Expansion) is my main end-to-end research artifact. It studies how expanding the effective receptive field changes sea-fog classification across multiple CNN backbones and two port environments.

The repository includes the paper, model implementations, training code, ERF measurement, Grad-CAM tooling, and full experiment summaries. Its reported best-mode comparison shows improvements in all eight backbone/port cases, with average Macro F1 gains of **+0.070 at Yeosu** and **+0.058 at Haeundae**.

### 2. Automated CV research intelligence

[**cv-research-radar**](https://github.com/Jung-woojin/cv-research-radar) continuously builds an evidence-oriented archive for:

- CV/VLM daily research briefs
- benchmark movement and evaluation changes
- failures, negative results, and reproducibility warnings
- research-question generation and minimal experiment design
- computer-vision open-source releases
- Japanese university CV laboratory monitoring
- biweekly trend maps across papers, code, and applications

The reports separate verified facts, author claims, and interpretation, then archive the same research output through a traceable Issue → Actions workflow.

### 3. AI developer-tool radar

[**agent-tool-radar**](https://github.com/Jung-woojin/agent-tool-radar) tracks MCP servers, skills, plugins, hooks, connectors, agent frameworks, and research-productivity tools. Candidates are evaluated by workflow value, installation model, permissions, maintenance, license, reproducibility, and a measurable trial rather than popularity alone.

## Featured work

| Project | What it contains | Why it matters |
|---|---|---|
| [Sea-Fog ERF Research](https://github.com/Jung-woojin/Sea-Fog-Classification-via-Kernel-Size-Scaling-Based-Effective-Receptive-Field-Expansion) | Paper, PyTorch models, ERF analysis, Grad-CAM, experiment results | Connects receptive-field design to a real maritime classification problem |
| [cv-research-radar](https://github.com/Jung-woojin/cv-research-radar) | Scheduled CV/VLM briefs, benchmark/failure watches, idea and trend reports | Converts fast-moving research into an auditable, reusable archive |
| [woojin-research-notes](https://github.com/Jung-woojin/woojin-research-notes) | Long-form reports on robust vision, multimodal AI, edge AI, data-centric vision, and surveillance systems | Bridges literature review, experiment questions, and system design |
| [computer-vision-compendium](https://github.com/Jung-woojin/computer-vision-compendium) | Integrated reference on detection, CNNs, signal processing, mathematics, and CVPR trends | A single entry point to the broader knowledge base |
| [object-detection-notes](https://github.com/Jung-woojin/object-detection-notes) | YOLO, DETR, RT-DETR, DINO, IoU losses, and open-vocabulary directions | A detection-first technical reference for model comparison |
| [signals-and-cv](https://github.com/Jung-woojin/signals-and-cv) | Frequency analysis, sampling, filtering, aliasing, and runnable toy experiments | Explains CV failures through signal-processing concepts |
| [CNN-From-Scratch-With-PyTorch](https://github.com/Jung-woojin/CNN-From-Scratch-With-PyTorch) | 14 CNN architectures plus a shared test and benchmark runner | Makes architecture differences inspectable in code |
| [cv_algebra](https://github.com/Jung-woojin/cv_algebra) | SVD/PCA, embedding geometry, curvature, low-rank modeling, and mini experiments | Uses linear algebra as a diagnosis and design tool for CV research |

## Research map

<details open>
<summary><strong>Research artifacts and experiment repositories</strong></summary>

| Repository | Scope |
|---|---|
| [Sea-Fog ERF Research](https://github.com/Jung-woojin/Sea-Fog-Classification-via-Kernel-Size-Scaling-Based-Effective-Receptive-Field-Expansion) | Large-kernel depthwise convolution, ERF expansion, maritime CCTV classification |
| [distance-estimation-2026](https://github.com/Jung-woojin/distance-estimation-2026) | Monocular/stereo depth, LiDAR fusion, NeRF, 3D Gaussian Splatting, and benchmarks |
| [code-for-simulation](https://github.com/Jung-woojin/code-for-simulation) | Reusable FFT, Grad-CAM, filtering, visualization, and experiment utilities |
| [CNN-From-Scratch-With-PyTorch](https://github.com/Jung-woojin/CNN-From-Scratch-With-PyTorch) | CNN implementations and a common comparison harness |
| [manim-theory-lab](https://github.com/Jung-woojin/manim-theory-lab) | Visual explanations of ERF and theoretical ideas with Manim |

</details>

<details>
<summary><strong>Research notes and knowledge bases</strong></summary>

| Repository | Scope |
|---|---|
| [computer-vision-compendium](https://github.com/Jung-woojin/computer-vision-compendium) | Integrated computer-vision reference and quick guide |
| [woojin-research-notes](https://github.com/Jung-woojin/woojin-research-notes) | Research reports, experiment protocols, and system documents |
| [computer-vision-research](https://github.com/Jung-woojin/computer-vision-research) | Long-term learning curriculum, research roadmap, and resource index |
| [cvpr-research-trends-2024-2025](https://github.com/Jung-woojin/cvpr-research-trends-2024-2025) | CVPR trend analysis with scripts and bilingual reports |
| [object-detection-notes](https://github.com/Jung-woojin/object-detection-notes) | Modern detector architectures, losses, and evaluation notes |
| [OVD_study](https://github.com/Jung-woojin/OVD_study) | Open-vocabulary and zero-shot detection concepts and model taxonomy |
| [CNN-receptive-field](https://github.com/Jung-woojin/CNN-receptive-field) | Theoretical and effective receptive field analysis |

</details>

<details>
<summary><strong>Mathematics, signals, and architecture foundations</strong></summary>

| Repository | Scope |
|---|---|
| [signals-and-cv](https://github.com/Jung-woojin/signals-and-cv) | Signal-processing explanations and CV-focused experiments |
| [signals-and-systems](https://github.com/Jung-woojin/signals-and-systems) | Fourier/Laplace/Z-transform, LTI systems, sampling, and filtering |
| [convolution_filter](https://github.com/Jung-woojin/convolution_filter) | Convolution mathematics, classic filters, efficient and dynamic convolution |
| [cv_algebra](https://github.com/Jung-woojin/cv_algebra) | Linear-algebra tools for representation, optimization, and efficient models |
| [algebra](https://github.com/Jung-woojin/algebra) | Practical linear-algebra notes for CV/DL researchers |
| [essential-mathematics-for-ai](https://github.com/Jung-woojin/essential-mathematics-for-ai) | Worked notebooks and extensions for AI mathematics |

</details>

## How I evaluate ideas

I prefer small experiments that can disprove an idea early. A typical study includes:

1. **Diagnosis** — define the failure mode before changing the architecture.
2. **Hypothesis** — state the mechanism that should change a measurable outcome.
3. **Minimum experiment** — isolate one factor with a strong baseline and controlled split.
4. **Evidence** — report class-wise metrics, efficiency, robustness, and negative results.
5. **Reuse** — preserve code, protocol, and interpretation so the result can guide the next study.

For deployed vision systems, I care about more than aggregate accuracy: domain shift, class imbalance, calibration, latency, memory, data leakage, and failure cases determine whether a model is actually useful.

## Technology

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![NVIDIA](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

**Methods:** CNNs · YOLO/DETR · vision-language models · self-supervised learning · frequency analysis · Grad-CAM · ERF measurement · ablation studies

**Research engineering:** experiment design · dataset splits · benchmark tracking · reproducible reports · GitHub Actions · edge deployment

## Collaboration

I am interested in collaborations around robust computer vision, maritime and coastal monitoring, efficient detection, receptive-field design, vision-language models, and research automation.

📫 **Email:** [wojin010629@gmail.com](mailto:wojin010629@gmail.com)<br>
🔗 **GitHub:** [github.com/Jung-woojin](https://github.com/Jung-woojin)

---

<div align="center">
<sub>Research notes become useful when they lead to a testable question, a reproducible experiment, or a better engineering decision.</sub>
</div>
