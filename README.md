# Neural Information Efficiency & Smartphone Addiction (SPA)
## A Computational Study via LIF Modeling and Information Theory

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Neuroscience](https://img.shields.io/badge/Field-Computational%20Neuroscience-red?style=for-the-badge)
![Math](https://img.shields.io/badge/Math-Information%20Theory-green?style=for-the-badge)

### 🧠 Research Overview
This project investigates the computational consequences of **Smartphone Addiction (SPA)** on neuronal information processing. By integrating neuroimaging evidence with a **Leaky Integrate-and-Fire (LIF)** modeling framework, we simulated how structural brain changes, specifically reduced Gray Matter Volume (GMV), translate into functional impairments.

The model focuses on the **Anterior Cingulate Cortex (ACC)** and the **Left Insula**, translating clinical findings into mathematical parameters:
* **Structural Degradation**: Simulated as decreased synaptic weight ($w=0.75$).
* **Functional Hypofunctionality**: Represented by increased synaptic noise ($\sigma=0.25$).

### 🛠️ Key Scientific Contributions
* **LIF Neuron Implementation**: Developed a single-compartment Leaky Integrate-and-Fire model to simulate membrane potential dynamics under stimulus.
* **Information Theory Metrics**: Applied **Entropy** and **Mutual Information (MI)** calculations to quantify the degradation of stimulus discrimination.
* **Parametric Sweep Analysis**: Identified a critical threshold at **60-70% connectivity**, revealing a phase transition where neural information transmission collapses.
* **Quantitative Findings**: Demonstrated a **64% reduction in Mutual Information** and a **58% decrease in firing rate** in SPA-like conditions compared to healthy controls.

### 📊 Key Results
* **Response Failure**: SPA-like neurons remained below the firing threshold in **60% of trials**, whereas healthy neurons maintained a 92% response rate.
* **Increased Stochasticity**: Output entropy rose from **0.557 to 0.965 bit**, indicating that addicted neuronal responses approach random noise.
* **Sensitivity Collapse**: Multi-stimulus testing revealed a **94% reduction** in the ability to detect medium-intensity stimuli.

### 📚 Scientific Reference
This computational model is grounded in the empirical research:
> **Horvath, J., Mundinger, C., Schmitgen, M. M., et al. (2020).** *Structural and functional correlates of smartphone addiction.* [Addictive Behaviors].
> [Link to Study]([https://doi.org/10.1016/j.addbeh.2020.106301](https://www.sciencedirect.com/science/article/abs/pii/S0306460319313802))

### 📂 Repository Structure
* `brain_mod_project.ipynb`: Core Python simulation, data analysis, and visualization.
* `report brain modelling.pdf`: Full academic report containing mathematical derivations and detailed discussion.
* `requirements.txt`: Project dependencies.

### 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/neural-info-spa.git](https://github.com/yourusername/neural-info-spa.git)
