# VulRepair Replication Study

This repository contains the **reproduction report** for *VulRepair: A T5-Based Automated Software Vulnerability Repair*. Our study investigates the reproducibility of VulRepair and analyzes how pre-training, tokenization, and dataset quality affect its performance.

📎 [Code Repository (Training Scripts, Logs, Pipeline)](https://github.com/rinaxosman/VulRepair)
🔗 [Original VulRepair Repository (by Fu et al.)](https://github.com/awsm-research/VulRepair)

---

## 📘 Overview

We re-implemented and evaluated all 10 variants of the VulRepair model on both the original and **deduplicated** versions of the CVEFixes dataset. Our evaluation focuses on four key research questions related to model accuracy, pre-training, tokenization, and component contributions.

---

## 🧪 Research Questions

1. **RQ1:** What is the accuracy of VulRepair for generating vulnerability repairs?
2. **RQ2:** What is the benefit of using pre-training?
3. **RQ3:** What is the impact of BPE tokenization?
4. **RQ4:** How do individual components (architecture, tokenizer, pre-training) contribute?

---

## 📄 What's in This Repo

- 📄 `paper-draft.tex` – Final LaTeX paper
- 📚 `refs.bib` – Bibliography file
- 📁 `sections/` – LaTeX sections (Intro, Methods, Results, etc.)
- 📊 `figures/` – Charts used in the report
- 📎 `acmart.cls` and related files – ACM conference template

---

## 📁 Paper Structure

- Introduction and background on ML-based vulnerability repair
- Description of VulRepair and its architecture
- Experimental setup (datasets, model configs, evaluation)
- Results and discussion across all 4 RQs
- Dataset deduplication impact
- Reproducibility insights

---

## 👥 Authors

- **Yushika Jhundoo** – University of Ottawa  
- **Rina Osman** – University of Ottawa  
- **Olena Naim** – University of Ottawa  
- **Supervised by:** Professor Paria Shirani

---

## 🔗 Links

- 🔬 Code, logs, and scripts: [https://github.com/rinaxosman/VulRepair](https://github.com/rinaxosman/VulRepair)
- 📄 Paper PDF: Coming soon