<div align="center">

# sruthi / work in progress

<sub>Computer science background · Biomedical engineering at NUS</sub>

`computer vision` &nbsp; / &nbsp; `machine learning` &nbsp; / &nbsp; `scientific computing`

</div>

---

```text
$ whoami
Sruthi Suresh

$ current_focus
Turning complex biological and clinical data into testable computational workflows.

$ selected_projects
01  computational-pathology
02  mimic-iv-icu-prediction
```

### 01 — [Computational pathology](https://github.com/sruthicodesthings/computational-pathology)

**From microscopy pixels to anatomical measurements.**

At EPFL, I worked on pathology segmentation and spatial analysis across large fluorescence microscopy datasets. The public case study reconstructs parts of the workflow: annotation-aware sampling, Attention U-Net training, tiled inference, and atlas registration.

<details>
<summary><code>open project notes +</code></summary>

```text
INPUT     multichannel fluorescence microscopy
MODEL     Attention U-Net / PyTorch / MONAI
PIPELINE  annotations → tiles → segmentation → registration
OUTPUT    spatially organized pathology measurements
```

Historical reported metrics and reconstructed code are documented separately; this is not a newly reproduced benchmark.

[Browse source and methodology](https://github.com/sruthicodesthings/computational-pathology)

</details>

### 02 — [ICU transfer prediction](https://github.com/sruthicodesthings/mimic-iv-icu-prediction)

**What could a model know at the time it makes a prediction?**

A MIMIC-IV research archive exploring hospital-to-ICU transfer risk with temporal features, multiple model families, calibration, and competing-risk formulations.

<details>
<summary><code>open project notes +</code></summary>

```text
INPUT     access-controlled MIMIC-IV hospital data
QUESTION  future ICU transfer after a prediction landmark
METHODS   temporal features / model comparison / calibration
CHECKS    leakage / patient splits / subgroup evaluation
DEMO      Streamlit research interface
```

Retrospective research only; not a validated clinical tool.

[Browse experiments and results](https://github.com/sruthicodesthings/mimic-iv-icu-prediction)

</details>

---

<details>
<summary><code>$ more about me</code></summary>

I started in computer science and moved into biomedical engineering because I wanted to work on computational problems with a direct connection to the physical world. I'm interested in computer vision, ML engineering, and data-focused roles across industries.

</details>

<sub>[all repositories](https://github.com/sruthicodesthings?tab=repositories)</sub>
