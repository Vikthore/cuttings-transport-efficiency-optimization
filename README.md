
# 🌿 Optimizing Cuttings Transport Efficiency with Natural Additives in Drilling Mud Systems

## Overview

This project explores the use of **natural additives—Terminalia Mantaly (TM)** and **Cocoyam (CY)**—as sustainable alternatives to the synthetic Poly-anionic Cellulose (PAC-R) for improving **Cuttings Transport Efficiency (CTE)** in drilling operations. Using machine learning and optimization techniques, this study offers a data-driven framework to evaluate and enhance mud system performance while reducing environmental impact.

---

## 📁 Project Structure

```
cte_natural_additives_dashboard.html   ← Static dashboard visualization (HTML)
README.md                              ← Project summary and methodology
```

---

## 🧪 Dataset & Experimental Design

- **TM/CY Dataset**: 6000 initial samples from lab experiments and correlations, resampled to 10,000 via interpolation
- **PAC-R Dataset**: 1000 standard-formulation samples
- **Key Parameters**:
  - Plastic Viscosity (PV)
  - Effective Mud Viscosity (EMV)
  - Cutting Rise Velocity (CRV)
  - TM and CY concentrations
  - Computed Cuttings Transport Efficiency (CTE)

---

## 🤖 Machine Learning Models

Three models were trained to predict CTE values:

| Model                 | R² Score     |
|----------------------|--------------|
| Random Forest (RFR)  | **0.9999**   |
| Artificial Neural Net| 0.9991       |
| Polynomial SVR       | 0.9857       |

- **Feature Importance**: Emphasized the influence of rheological properties like PV and EMV
- **Model Evaluation**: RFR demonstrated superior generalization and predictive robustness

---

## ⚙️ Optimization Insights (via Optuna)

- Optimal blend found:  
  - **TM = 0.25 g/cm³**  
  - **CY = 2.75 g/cm³**  
  - **Constraint**: TM + CY = 3  
  - **Max Predicted CTE**: 0.6684

This highlights the tunability of natural additives for optimal performance.

---

## 📊 Comparative Analysis with PAC-R

- **Approach**: Nearest neighbor pairing, statistical hypothesis testing
- **Findings**:  
  - PAC-R outperformed TM/CY in fixed-formulation trials  
  - TM/CY offers customizable performance with environmental benefits

---

## 💡 Key Takeaways

- Natural additives TM and CY are viable, eco-friendly options for improving CTE.
- Machine learning models can accurately model and optimize drilling fluid performance.
- Optuna enables effective multi-variable optimization within chemical constraints.
- Rheological control remains central to wellbore cleaning efficiency.

---

## 🔬 Future Work

- Validate findings with real-world well data
- Investigate hybrid mud systems combining PAC-R with TM/CY
- Study long-term environmental and cost impacts of natural additives

---

## 📫 Contact

**Victor Ikechukwu**  
📧 Email: [vikechukwu43@gmail.com](mailto:vikechukwu43@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/victor-ikechukwu-1169942a7](https://www.linkedin.com/in/victor-ikechukwu-1169942a7?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
📍 Location: Port Harcourt, Nigeria
