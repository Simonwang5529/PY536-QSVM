# Quantum Support Vector Machine (QSVM) Implementation and Performance Analysis

This repository contains the implementation and performance analysis of a **Quantum Support Vector Machine (QSVM)**, where QSVM_local.ipynb is the final version of the project. 

QSVM1 is the one with connection to the IBM quantum computer, but my account got banned. 

The project explores the capabilities of QSVM in handling non-linear datasets and compares its performance to classical Support Vector Machines (SVM). 
---

## Contents

### **1. Notebooks**
1. **`qsvm_local.ipynb`**  
   - The final version of the course project, implemented using a local quantum simulator.  
   - Includes valid code, write-up, and performance analysis.  
   - This notebook serves as the complete and polished submission.

2. **`QSVM1.ipynb`**  
   - An earlier version that attempted to connect to the IBM Quantum Computer.  
   - While a connection was successfully established once, long queues and subsequent account issues necessitated completing the project using local simulators.

---

## **Notes**
- In the presentation, I reported an accuracy improvement with QSVM when running the **Heart Disease Dataset**. However, further analysis revealed that part of the improvement was due to imbalances in the dataset.  
- This updated version addresses those issues by preprocessing the data more rigorously, offering a deeper interpretation of accuracy performance for both QSVM and classical SVM models.
- Qiskit is updated frequently, some libraries in this notebook may be deprecated in the future, please keep track of the IBM documentation.
- **ChatGPT Contribution**: ChatGPT was utilized for minor tasks such as code rearrangement, data loading, and improving code readability to ensure a better presentation.

---

## **Datasets**
- The datasets used in this project are included in the repository.
- Alternatively, you can download them using the links provided in the `qsvm_local.ipynb` notebook.

---

## **Libraries and Dependencies**
Ensure you have the following libraries installed to run the notebooks:

### **Quantum Libraries**
- `qiskit`
- `qiskit-machine-learning`
- `qiskit-aer`

### **Machine Learning Libraries**
- `scikit-learn`
- `imbalanced-learn`

### **Numerical and Visualization Libraries**
- `numpy`
- `pandas`
- `matplotlib`

To install all dependencies, run:
```bash
pip install qiskit qiskit-machine-learning scikit-learn imbalanced-learn numpy pandas matplotlib
