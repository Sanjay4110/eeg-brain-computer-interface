# 🧠 EEG Brain-Computer Interface for Hand Movement

This project aims to characterize the brain waves associated with controlled hand movements using EEG data. The goal is to develop a system that records and analyzes EEG signals to identify neural patterns linked to motor actions, ultimately enabling applications in brain-computer interfaces (BCIs) and neurorehabilitation.

---

## 📄 Project Synopsis

Understanding brain activity related to voluntary hand movement is critical for advancing assistive technologies. This project focuses on:
- **Recording EEG Signals:** Using an Ultracortex “Mark IV” EEG Headset to capture brain activity during controlled hand movements.
- **Signal Processing:** Applying filtering, noise reduction, and feature extraction (e.g., wavelet transform, power spectral density estimation) to analyze key frequency bands such as Alpha, Beta, and Mu rhythms.
- **Real-Time Visualization:** Integrating a system that displays EEG signals on a monitor as the subject moves a cursor, providing immediate feedback.
- **Machine Learning:** Training models to classify hand movement patterns based on the extracted EEG features.

For detailed project information, refer to the [Project Synopsis (PDF)](./docs/synopsis_phase1_draft.pdf).

---

## 🎯 Objectives

- Record EEG signals associated with hand movement.
- Refine methods for acquiring and preprocessing EEG data.
- Detect characteristic patterns linked to cursor displacement.
- Evaluate the efficacy of mouse or touchpad movement using EEG data.

---

## 🚀 Features

- **Non-Invasive EEG Recording:** Capturing brain waves via the Ultracortex EEG headset.
- **Signal Processing Pipeline:** Noise reduction and feature extraction using standard techniques.
- **Real-Time Visualization:** Displaying EEG signals and corresponding cursor movement feedback.
- **Machine Learning Integration:** Preliminary classification of hand movements based on EEG patterns.

---

## 🖥️ Software & Hardware Requirements

### Hardware
- **Ultracortex “Mark IV” EEG Headset:** For capturing EEG signals.
- **LED Display:** To provide visual feedback during experiments.
- **Mouse/Touchpad:** For evaluating movement efficacy and interfacing with the system.

### Software
- **OpenBCIgui Software:** To interface with the EEG headset and visualize raw data.
- **MATLAB:** For advanced signal processing, feature extraction, and visualization.
- **Python:** For developing the preprocessing pipeline and machine learning models. Libraries such as NumPy, SciPy, MNE, matplotlib, and scikit-learn are recommended.
- **Jupyter Notebook:** For interactive exploratory analysis.

---
## 🙏 Credits

This project is being developed as part of an academic research initiative under the Department of Electrical and Electronics Engineering, BMS Institute of Technology & Management.

Special thanks to our guide Dr. Prashanth A Athavle for their valuable insights and support.

Developed by:

- Sanjay R [GitHub: [@Sanjay4110](https://github.com/Sanjay4110)]


## 📁 Project Structure

```plaintext
eeg-brain-computer-interface/
├── README.md                       # Project overview and instructions
├── docs/
│   └── synopsis_phase1_draft.pdf   # Detailed project synopsis
├── notebooks/                      # Jupyter notebooks for exploratory analysis
│   └── exploratory_analysis.ipynb  # Example analysis and visualization code
└── src/                           # Source code for signal processing and ML
    └── preprocessing.py           # Preprocessing routines for EEG data




