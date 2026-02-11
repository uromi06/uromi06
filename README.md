<!-- Banner -->
<p align="center">
  <img src="https://raw.githubusercontent.com/uromi06/uromi06/main/Urmi%20Banner.png" alt="Urmi Banner" width="100%">
</p>

# 👋 Hi, I’m Urmi!

🎓 Biomedical Engineer focused on advancing AI-driven medical imaging and clinically meaningful healthcare technology.
🔬 I develop and evaluate deep learning pipelines for explainable diagnosis, MRI analysis, and quantitative biomarker estimation. 

---

## 🛠️ Technical Skills  

<table>
<tr>
<td valign="top" width="52%">

<b>Programming & Data Science</b><br><br>

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="30" align="left"> <b>Python</b><br><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="30" align="left"> <b>PyTorch</b><br><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/numpy/numpy-original.svg" width="30" align="left"> <b>NumPy</b><br><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="30" align="left"> <b>TensorFlow</b><br><br>


</td>
<td valign="top" width="50%">

<b>Medical Imaging & Viz Tools</b><br><br>
<a href="https://git.fmrib.ox.ac.uk/fsl">
  <img src="https://raw.githubusercontent.com/uromi06/uromi06/main/fsl-logo-x2.png" width="30" align="left">
</a> <b>FSL</b><br><br>
<a href="https://www.mevislab.de/de/">
  <img src="https://raw.githubusercontent.com/uromi06/uromi06/main/mevislab.jpg" width="30" align="left">
</a> <b>MeVisLab</b><br><br>
<a href="https://www.mrtrix.org">
  <img src="https://raw.githubusercontent.com/uromi06/uromi06/main/mrtrix.jpg" width="30" align="left">
</a> <b>MRtrix3</b><br><br>
<a href="https://www.paraview.org">
  <img src="https://raw.githubusercontent.com/uromi06/uromi06/main/paraview.jpg" width="30" align="left">
</a> <b>ParaView</b><br><br>


</td>
</tr>
</table>

---

## 📂 Research Projects  

### 🩺 [Chest X-Ray XAI — Pneumonia Detection with Explainable Deep Learning](https://github.com/uromi06/chestxray-xai)

- Built an **end-to-end PyTorch pipeline** for pediatric pneumonia detection from chest X-rays using a fine-tuned **ResNet-18** backbone.  
- Achieved **AUROC = 0.979**, **AUPRC = 0.985**, with **Sensitivity = 0.997** (screening) and **Precision = 0.94** (rule-in mode).  
- Applied **Grad-CAM** visualizations to highlight pulmonary opacities, ensuring **transparency** and **clinical interpretability**.  
- Implemented **temperature scaling** and **Youden’s J** threshold tuning for **probability calibration** and operating-point flexibility.  
- Emphasized **explainability**, **robust evaluation**, and **reproducible design** for research-grade medical imaging AI.


---

### 🔬  [CMRO₂ Project — Cerebral Metabolic Rate of Oxygen Based on Synthetic Cerebral Blood Volume Maps](https://github.com/uromi06/CMRO2-Project-Public)   
- Built a **3D U-Net conditional GAN** to synthesize **CMRO₂ maps** from multimodal quantitative MRI (CBV, CBF, T2, T2*).  
- Preprocessing included GM masking, MNI152 resampling, and normalization.  
- Achieved high accuracy with all modalities (MSE ~0.0007, SSIM ~0.92, Pearson r ~0.95).  
- Demonstrated that **vascular modalities (CBV & CBF)** are essential for reliable CMRO₂ estimation.

---
<!--
### 🧪 Master Thesis (in progress) — *fabberpy*: Python Bayesian Modeling for ASL  
- Implementing selected Fabber forward models in pure Python, focusing on Bayesian estimation for multi-echo (TE) and multi-inversion time (TI) ASL data.  
- Validating against synthetic and age-related cohorts using voxel-/ROI-wise comparisons.  
- Extending modeling to evaluate fitted vs. fixed T2 values, improving robustness across populations.    
-->
---

### 🏆 [SugarIQ — Diabetes Management Platform (1st Place, Healthcare Hackathon Bayern 2025)](https://github.com/uromi06/sugariq-diabetes-management-platform)
- Co-developed **SugarIQ**, an AI-enabled diabetes management platform built in 48 hours, featuring real-time patient monitoring, health trend visualization, medication tracking, and AWS-powered live consultation workflows (Transcribe Medical).  
- Contributed to **synthetic data generation and patient modeling** using BRFSS health indicators, enabling realistic patient datasets for analysis; platform built with React + TypeScript, AWS Lambda, API Gateway, S3, and Python-based data engineering.

### 🧠 [Mitigating Shortcut Learning for Medical Imaging (UBRA Hackathon 2025)](https://github.com/uromi06/Mitigating-Shortcut-Learning-for-Medical-Imaging)
- Implemented **Supervised Contrastive Learning (SupCon)** loss to improve representation learning for chest X-ray classification under **spurious shortcut cues** (e.g., chest-drain bias).
- Built a reusable **SupConLoss** module with label-aware positive/negative pairing, **temperature scaling**, and stable feature normalization for medical-image embeddings.
- Integrated SupCon into the training pipeline alongside the classification objective, enabling ablation studies comparing **ERM vs. SupCon-regularized training** for shortcut robustness.
- Added configuration hooks (loss weighting/temperature) so the loss can be toggled cleanly for experiments without modifying model code.


---
✨ *“Advancing healthcare through imaging, AI, and biomedical engineering.”*
