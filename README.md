# Quantum-Enhanced Astrocytoma Classifier

“Quantum‐enhanced astrocytoma classifier: variational quantum circuits + hybrid PyTorch model”

---

## 📖 Project Overview

This repository contains a proof-of-concept pipeline that:

1. **Extracts radiomic features** from pediatric astrocytoma MRI scans.  
2. **Builds a classical baseline** model (Random Forest or small CNN) for low- vs. high-grade classification.  
3. **Implements a hybrid quantum-classical network** by replacing a dense layer with a variational quantum circuit (using PennyLane).  
4. **Compares performance** (AUC, loss curves) between the classical and hybrid approaches.

---

## 🚀 Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/drbroderickcrawford/astrocytoma-hybrid.git
cd astrocytoma-hybrid
### 2. Create your environment


### 3. Download Data

- **BraTS-Paed** (public pediatric glioma MRI)  
  1. Sign up at [BraTS on Kaggle](https://www.kaggle.com/c/brats-20).  
  2. Download the training images and segmentations.  
  3. Convert to NIfTI if needed (e.g., via `dcm2niix`).  
- **CBTTC** (Children’s Brain Tumor Tissue Consortium)  
  1. Register for free on the [CBTTC Data Portal](https://portal.cbttc.org).  
  2. Download astrocytoma MRI cases and associated clinical metadata.

See `data/README.md` for detailed steps.




