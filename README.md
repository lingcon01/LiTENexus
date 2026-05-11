# LiTENexus

<div align="center">

<h2>An End-to-End Virtual Drug Discovery System Based on Quantum Chemical Grounding</h2>

<p>
  Physics-informed molecular intelligence for next-generation AI-driven drug discovery
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
  <img src="https://img.shields.io/badge/PyTorch-2.0+-red.svg">
  <img src="https://img.shields.io/badge/License-Apache%202.0-green.svg">
  <img src="https://img.shields.io/badge/Status-Active-success.svg">
</p>

</div>

---

## ✨ Overview

LiTENexus is a physics-grounded, end-to-end AI-aided drug discovery (AIDD) framework designed to bridge microscopic quantum chemical principles with macroscopic pharmacological applications. The system is built upon the **Quantum Chemical Information Injection (QCII)** mechanism and powered by the foundational **LiTEN-Base** operator.

Unlike conventional molecular representation models that primarily learn statistical correlations from data, LiTENexus dynamically integrates quantum chemical laws into neural operators, enabling:

- 🔬 Enhanced out-of-distribution (OOD) generalization
- 🧠 Improved mechanistic interpretability
- ⚛️ Quantum-level microscopic property prediction
- 💊 High-performance ADMET prediction
- 🔗 Cross-modal virtual screening
- 🚀 End-to-end virtual drug discovery workflows

---

## 🌟 Key Features

### ⚛️ Quantum-Chemical Grounded Representation Learning

- Physics-informed neural operator architecture
- Dynamic injection of quantum chemical information
- Field reconstruction paradigm for spatial topology and polarization modeling
- Unified latent representation across molecular tasks

### 🧪 Microscopic Property Prediction

- Quantum-level accuracy comparable to DFT methods
- 2–3 orders of magnitude faster than conventional DFT calculations
- Support for:

  - Energy prediction
  - Force prediction
  - Charge distribution
  - Bond dissociation energy (BDE)
  - Molecular conformational analysis

### 💊 ADMET Modeling

- State-of-the-art performance across multiple benchmarks
- Strong generalization to:

  - Natural products
  - Cyclic peptides
  - Complex out-of-distribution molecular spaces

- Multi-task pharmacokinetic property prediction

### 🔍 Virtual Screening

- Quantum Manifold Dense Retrieval (QMDR)
- Cross-modal molecular representation alignment
- Efficient ligand retrieval and ranking
- High enrichment performance on benchmark datasets

---

## 🧩 Modular Ecosystem

LiTENexus is composed of multiple interoperable modules:

| Module | Description |
|---|---|
| **LiTEN-Base** | Foundational quantum-aware representation operator |
| **LiTEN-FF** | Molecular force field and conformational modeling |
| **LiTEN-Micro** | Microscopic physicochemical property prediction |
| **LiTEN-ADMET** | Pharmacokinetic and toxicity prediction |
| **LiTENCLIP** | Cross-modal molecular retrieval and screening |

---

## 🏗️ System Architecture

```text
               Microscopic Quantum Dynamics
                              │
                              ▼
      Quantum Chemical Information Injection
                         (QCII)
                              │
                              ▼
         LiTEN-Base Universal Representation Engine
                              │
       ┌──────────────┬──────────────┬──────────────┬
       ▼              ▼              ▼              ▼
      LiTEN-FF    LiTEN-Micro   LiTEN-ADMET    LiTENCLIP
       │              │              │              │
      Conformation  Physicochemical  ADMET      Virtual
      Modeling      Properties       Prediction  Screening
```

---

## 🚀 Highlights

- ⚛️ Quantum-chemically grounded molecular representation learning
- 🌍 Strong OOD generalization ability
- 🔄 Unified microscopic-to-macroscopic modeling pipeline
- 🧠 Physics-aware neural operator architecture
- 🔍 Scalable virtual screening framework
- 🧩 Modular and extensible design

---

## 📊 Benchmark Performance

### 💊 ADMET Prediction

- Outperformed more than 20 baseline models on proprietary datasets
- Achieved leading performance on:

  - PharmaBench
  - Biogen
  - ADMETLAB 3.0

### 🔍 Virtual Screening

| Dataset | Performance |
|---|---|
| DUD-E | High enrichment performance |
| LIT-PCBA | Strong retrieval capability |

### ⚛️ Quantum Property Modeling

- Near-DFT-level prediction accuracy
- Significant computational acceleration compared with traditional quantum chemistry methods

---

## 🧬 Applications

LiTENexus can be applied to:

- AI-aided drug discovery
- Molecular property prediction
- ADMET optimization
- Lead compound screening
- Molecular generation
- Conformation analysis
- Quantum chemistry acceleration
- Physics-informed molecular modeling

---

## 🌐 Online Platform

We are actively developing the public **LiTENexus Platform** to provide open access to quantum-aware molecular modeling and AI-driven drug discovery tools.

The platform will support:

- ⚛️ Quantum-level molecular property prediction
- 💊 ADMET evaluation
- 🧪 Molecular conformation optimization
- 🔍 Cross-modal virtual screening
- 🔗 Molecular retrieval and ranking
- 🤖 Interactive AI-assisted drug discovery workflows

### 🔗 Platform Access

👉 **Our platform will be publicly available at:**  
**https://cadd.zju.edu.cn/litenexus/**

Stay tuned for future releases and updates.

---

## 📖 Citation

If you find this project useful in your research, please cite:

```bibtex
@article{litenexus2026,
  title={LiTENexus: An End-to-End Virtual Drug Discovery System Based on Quantum Chemical Grounding},
  author={Su, Qun and Gou, Qiaolin and Dai, Mengzhe and others},
  journal={Under Review},
  year={2026}
}
```

---

## 📬 Correspondence

- Tingjun Hou — [tingjunhou@zju.edu.cn](mailto:tingjunhou@zju.edu.cn)
- Jike Wang — [jikewang@zju.edu.cn](mailto:jikewang@zju.edu.cn)
- Chang-Yu Hsieh — [kimhsieh@zju.edu.cn](mailto:kimhsieh@zju.edu.cn)
- Yu Kang — [yukang@zju.edu.cn](mailto:yukang@zju.edu.cn)

---

## 📄 License

This project is licensed under the Apache License 2.0.

---

## 🙏 Acknowledgements

We thank all collaborators and contributors involved in the development of LiTENexus and related quantum chemistry and AI-driven drug discovery research.

---

## ⭐ Star History

If you find this repository useful, please consider giving it a ⭐ on GitHub.
