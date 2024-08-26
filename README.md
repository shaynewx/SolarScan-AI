# Solar Panel Defect Classification
This project aims to classify solar panel defects using machine learning and computer vision techniques, specifically employing the Electroluminescence (EL) technology to analyze images for potential defects. We developed and validated a system that can predict the health of solar modules and classify them according to the likelihood of defects.

## Overview
Solar panels are prone to defects from various sources such as falling tree branches, hail, or manufacturing issues. Early and accurate detection of these defects is crucial for maintaining efficiency and functionality. Our model uses EL images, where damaged areas appear darker, to automatically detect and categorize these defects.

## Dataset
We utilized the ELVP dataset, which includes 2,624 samples of 300x300 pixel 8-bit grayscale images showing solar cells in normal and various degraded conditions. The dataset is standardized and manually annotated with defect probability values and cell types (monocrystalline or polycrystalline).

## Machine Learning Models Used
- **Decision Trees**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **Stochastic Gradient Descent (SGD)**
- **Convolutional Neural Networks (CNN)**
Initial tests were performed using simpler machine learning algorithms such as SVM and SGD. Based on the performance, we further explored CNN models for better classification accuracy.

## Contribution
Contributions are welcome. Please fork the repository and open a pull request with your suggested changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

