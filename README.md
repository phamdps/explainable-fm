<div align="center">

# 🌟 Explainable Foundation Models

</div>


<p align="center">
  <img src="assets/explainable.gif" alt="Explainable Autonomous Cognitive Transportation Digital Twin" width="800"/>
</p>

> *A next-generation digital twin framework bridging real-time traffic simulation, **Explainable Time Series Foundation Models**, and **Multimodal Large Language Models (MLLMs)** for transparent, human-aligned autonomous systems.*

---

## 🌟 Overview

As autonomous driving and smart city infrastructures scale, traditional "black-box" models struggle with safety, interpretability, and long-horizon temporal forecasting. This repository presents an **Explainable Autonomous Cognitive Transportation Digital Twin** that merges state-of-the-art foundation models with real-time digital twin environments[cite: 2]. 

A core innovation of this framework is the seamless synergy between **Time Series Foundation Models** and **Multimodal Large Language Models (MLLMs)**: the predictive and anomaly-detection outputs of the time series foundation models are directly fed into the MLLMs as structured contextual tokens[cite: 2]. This empowers the MLLM to perform advanced semantic reasoning, contextualize temporal trends with visual and textual cues, and output natural language justifications for every driving decision[cite: 2].

---

## ⚙️ Core Architecture & Technologies

- **Time-Series-to-MLLM Bridge:** Numerical outputs, confidence scores, and feature attributions from time series foundation models are formatted and injected into MLLMs, allowing language models to "reason" over temporal traffic trajectories and anomalies[cite: 2].
- **Multimodal Large Language Models (MLLMs):** Fuse multi-camera video streams, LiDAR inputs, and time-series-derived insights to generate high-level semantic reasoning and natural language justifications[cite: 2].
- **Explainable Time Series Foundation Models:** Leverage pre-trained temporal transformers to capture long-range dependencies, complex traffic flow dynamics, and anomalies with native feature attribution maps[cite: 2].
- **Cognitive Digital Twin Engine:** Simulates complex urban and highway driving ecosystems in real time, synchronizing physical telemetry with virtual environment states[cite: 2].
- **Explainable AI (XAI) Layers:** Translates deep latent representations into human-interpretable metrics, attention heatmaps, and confidence scores[cite: 2].

---

## 🚀 Key Features

- **Synergistic Temporal Reasoning:** Bridging quantitative time-series forecasting results with qualitative MLLM reasoning for holistic traffic intelligence[cite: 2].
- **Transparent Decision-Making:** Trace back *why* an autonomous agent made a specific maneuver using integrated MLLM justifications backed by precise time series forecasts[cite: 2].
- **Robust Temporal Forecasting:** Out-of-time-the-box performance on predicting traffic congestion, pedestrian movement, and vehicle trajectories using foundation models[cite: 2].
- **Interactive Digital Twin Environment:** Seamless synchronization between real-time inference pipelines and visualization modules[cite: 2].

---

## 📂 Repository Structure

```text
├── assets/                  # GIFs, diagrams, and media files
├── src/
│   ├── models/              # Time series foundation models, MLLMs, & bridge modules
│   ├── digital_twin/        # Simulation environment and sensor sync
│   └── xai/                 # Explainability modules and attribution extractors
├── configs/                 # Hyperparameter and model configuration YAMLs
├── scripts/                 # Training, evaluation, and deployment scripts
├── notebooks/               # Interactive tutorials and demo walkthroughs
└── README.md

```

---

## 🛠️ Quick Start

### Prerequisites

* Python 3.10+
* PyTorch 2.0+
* CUDA-enabled GPU recommended for MLLM inference

### Installation

```bash
# Clone the repository
git clone [https://github.com/phamdps/explainable-fm.git](https://github.com/phamdps/explainable-fm.git)
cd explainable-fm

# Install dependencies
pip install -r requirements.txt

```

### Running a Simulation Demo

```bash
python scripts/run_simulation.py --config configs/default_twin.yaml

```

---

## 📄 Citation

If you use this framework or code in your research, please cite our work:

```bibtex
@article{explainable_digital_twin_2026,
  title={Explainable Autonomous Cognitive Transportation Digital Twin using Time Series Foundation Models and MLLMs},
  author={Phuong Pham / Explainable Digital Twin},
  year={2026}
}

```

---

## 📜 License

Distributed under the [MIT License](https://www.google.com/search?q=LICENSE).
