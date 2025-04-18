# Project Overview

This project is the author's 2025 final year project at the University of Liverpool: *Meta-learning for Signal Detection in Wireless Networks.*

This project implements wireless network signal detection models based on Deep Learning (DL) and Meta-Learning, aiming to enhance adaptability and performance in dynamic wireless environments.

## Project Structure

### Python Files:

- **`singal_detection_withOFDM.py`**:

  - Provides OFDM (Orthogonal Frequency Division Multiplexing) signal generation, simulation, and implementations for traditional Deep Neural Networks (DNN) and Meta-Learning models (MetaDNN).
  - Includes channel simulations (Rayleigh, Rician, AWGN, WINNER II, etc.) and evaluation methods.

- **`ExperimentConfig.py`**:

  - Manages comprehensive experimental configuration parameters, supporting experiment reproducibility.
  - Defines simulation parameters, dataset sizes, model structures, and training parameters.

- **`matlab_export.py`**:

  - Exports model training and testing performance metrics (such as Bit Error Rate, BER) into MATLAB-compatible data files for subsequent analysis.

## Data Information

The generation of WINNER II channel data relies on the channel response file `channel_train.npy`. Due to its size, the file cannot be uploaded here. Please refer to: [OFDM\_DNN GitHub repository](https://github.com/haoyye/OFDM_DNN).

## Log Book Description

The Log Book documents my exploratory learning in machine learning and signal processing, including several attempts at experiment construction. After the basic functionality of the experimental programs was implemented, it recorded results, attempts to test hypotheses, and optimizations for the experiments.

## Environment Setup

Detailed dependencies are listed in the `requirements.txt` file.

The project requires libraries such as TensorFlow, NumPy, and Matplotlib, with specific version details provided in the above-mentioned file.

---

For further information or guidance, please contact the project author or refer to the code comments.

