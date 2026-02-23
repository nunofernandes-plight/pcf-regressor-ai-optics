# Project: AI-Optics-PCF-Regressor  

 ## An Ultra-Fast Neural Network Proxy for Photonic Crystal Fiber Design.

### 1. Overview
This repository provides a machine-learning-based surrogate model for characterizing Specialty Optical Fibers. By training on high-fidelity FEM data, the engine predicts the Complex Effective Index ($n_{eff}$) and Dispersion ($D$) without the need for intensive Maxwell solvers.

### 2. Installation 

#### Clone the repository
```bash
git clone https://github.com/your-org/ai-optics-pcf-regressor.git
cd ai-optics-pcf-regressor
```

#### Install dependencies
```bash
pip install -r requirements.txt
```
# 4. Configuration & Software Scripts
requirements.txt

```bash
numpy>=1.24.0
pandas>=2.0.0
scikit-learn>=1.3.0
joblib>=1.3.0
matplotlib>=3.7.0
```
setup.py (For distribution) 

```Python
from setuptools import setup, find_packages

setup(
    name="ai-optics-pcf-regressor",
    version="1.0.0",
    packages=find_packages(),
    install_requires=[
        'numpy', 'pandas', 'scikit-learn', 'joblib'
    ],
    author="Photonics AI Team",
    description="ML-Accelerated Specialty Fiber Design Engine",
    classifiers=[
        "Programming Language :: Python :: 3",
        "Topic :: Scientific/Engineering :: Physics",
    ],
)
```
