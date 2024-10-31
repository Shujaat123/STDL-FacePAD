# Spatio-Temporal Deep Learning for Improved FacePAD

![Spatio_Temporal_Averaging_CNN](https://github.com/user-attachments/assets/75f4d407-1601-47cd-99de-e3a30e628116)

## Overview
This repository contains the implementation of the Spatio-Temporal Deep Learning for Improved Face Presentation Attack Detection (FacePAD) approach. This work addresses the critical need for robust and efficient face presentation attack detection (PAD) systems in biometric security, targeting spoofing methods like printed photos, video replays, and 3D masks. Leveraging a lightweight CNN (MobileNetV3) and spatio-temporal feature extraction, this method achieves high detection accuracy with minimal computational cost.

## Key Features
- **Model Architecture**: Utilizes MobileNetV3 for spatial feature extraction, enhanced by a temporal average pooling layer to capture dynamic patterns in video sequences.
- **High Efficiency**: Designed for real-time performance, suitable for mobile and resource-constrained environments.
- **Dataset Compatibility**: Validated on multiple datasets, including Replay-Attack, Replay-Mobile, and ROSE-Youtu, showing high accuracy and robustness against diverse attack types.


## Usage

### Running the Jupyter Notebook:
1. Open the notebook `RY_SpatioTemporal_CNN_FacePAD_random_K_frames_SupervisedLearning_SKv1.ipynb` to explore the training and evaluation process.
2. In the notebook, you can adjust parameters, including the number of frames for spatio-temporal analysis and model configuration.
3. Execute each cell sequentially for end-to-end training, evaluation, and visualization of results.

To launch the notebook, run:
```bash
jupyter notebook RY_SpatioTemporal_CNN_FacePAD_random_K_frames_SupervisedLearning_SKv1.ipynb
```

## Citation
If you use this work, please cite:

@article{Khan2024FacePAD,
  title={Spatio-Temporal Deep Learning for Improved FacePAD},
  author={Shujaat Khan, Muhammad Sohail Ibrahim, Taha Hasan Masood Siddique, Abdul Jabbar Siddiqui, and Kejie Huang},
  journal={XXXX},
  year={2024},
  note={Supported by the Saudi Data and AI Authority (SDAIA) and KFUPM under JRC-AI-RG-15}
}
