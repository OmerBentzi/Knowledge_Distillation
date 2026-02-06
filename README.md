# Knowledge Distillation

This repository contains the research project **"Knowledge Distillation"**, focusing on enhancing Knowledge Distillation (KD) techniques by integrating **Attention Transfer (AT)** and **Feature Alignment (FA)** guided by causal attention masking. The project demonstrates how structured and selective attention mechanisms can significantly improve student model performance in terms of accuracy, generalization, and robustness while maintaining model efficiency.

## 📄 Project Paper
You can read the full research paper here:
👉 [View PDF Paper](./Knowledge_Distillation_Article.pdf)


## 🧠 Key Contributions
- A unified KD framework combining **Attention Transfer (AT)** and **Feature Alignment (FA)**.
- Introduction of **causal masking** to filter irrelevant teacher attention regions.
- Empirical evaluation on **CIFAR-10**, showing significant performance improvements over baseline KD methods.
- Robustness analysis on corrupted inputs, highlighting the advantages of selective attention alignment.

## 🏆 Results Summary
| Configuration                      | Validation Accuracy (%) |
|------------------------------------|-------------------------|
| Baseline (Cross-Entropy Only)      | 80.56%                  |
| Standard KD (CE + KL Divergence)   | 83.64%                  |
| KD + Feature Alignment (FA)        | 82.78%                  |
| KD + Attention Transfer (AT)       | 83.53%                  |
| KD + Combined Method (FA + AT)     | **83.77%**              |



## 👨‍💻 Authors
- **Omer Ben Simon**
- **Roei Aviv**
- **Yuval Loria**

Department of Intelligent Systems Engineering, Afeka College of Engineering, Tel Aviv, Israel

## 📜 License
This project is for academic research purposes only.

---
Feel free to ⭐ star this repository if you find it useful!
