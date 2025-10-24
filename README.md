
# **“EEG Sleep Cycle Prediction.”**
## Aim :
> A machine learning model to analyze and predict human sleep stages using EEG signals.

---

##  Overview

This project focuses on **predicting human sleep cycles** from EEG data by identifying distinct stages such as **awake, REM, light sleep, and deep sleep**. Using advanced machine learning and deep learning techniques, the model classifies EEG time-series data to support **sleep research and health monitoring**.

---

##  Methodology

1. **Data Loading:** EEG data sourced from open datasets (e.g., Sleep-EDF, PhysioNet).
2. **Preprocessing:**

   * Band-pass filtering (0.5–45 Hz)
   * Normalization and window segmentation
   * Label encoding of sleep stages
3. **Feature Extraction:** Power spectral density, entropy, and temporal characteristics.
4. **Modeling:**

   * Classical ML: Random Forest, SVM
   * Deep Learning: LSTM / CNN for temporal sequence prediction
5. **Evaluation:** Compared results on validation and test splits for sleep stage classification.

---

##  Tech Stack

| Category              | Tools / Frameworks                                                 |
| --------------------- | ------------------------------------------------------------------ |
| **Language**          | Python                                                             |
| **Libraries**         | NumPy, Pandas, Matplotlib, SciPy, Scikit-learn, TensorFlow / Keras |
| **Signal Processing** | MNE, PyEEG                                                         |
| **Visualization**     | Matplotlib, Seaborn                                                |

---

##  Results

* Achieved **high classification accuracy (~90%)** for major sleep stages.
* Clear improvement in detection of REM and Deep Sleep stages using EEG frequency features.

---
 
##  References

* Sleep-EDF Database [PhysioNet](https://physionet.org/content/sleep-edfx/1.0.0/)
* MNE-Python and TensorFlow official documentation

---
