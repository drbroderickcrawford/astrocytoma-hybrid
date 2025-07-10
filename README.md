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


