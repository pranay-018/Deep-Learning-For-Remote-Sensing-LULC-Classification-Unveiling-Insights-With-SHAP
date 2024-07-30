# LULC Classification with CNN and SHAP

This repository presents a deep learning framework for Land Use and Land Cover (LULC) classification using Sentinel-2 satellite imagery. The framework features a compact Convolutional Neural Network (CNN) combined with Shapley Additive Explanations (SHAPs), providing both efficiency and interpretability. It employs three-band combinations to achieve superior performance on the EuroSAT dataset, demonstrating effectiveness in resource-constrained environments. SHAP values offer insights into the importance of input features, enhancing transparency in the model's predictions and aiding decision-making. While the current implementation does not include Liquid Neural Networks (LNN), we plan to integrate LNN in the future for real-time learning and improved adaptability. This approach aims to advance state-of-the-art techniques in remote sensing-based LULC classification, supporting more reliable and sustainable land management practices.

## Project Overview

- **Model:** Convolutional Neural Network (CNN)
- **Data:** Sentinel-2 satellite imagery (EuroSAT dataset)
- **Features:** Uses three-band combinations for classification
- **Interpretability:** Shapley Additive Explanations (SHAPs)
- **Future Work:** Integration with Liquid Neural Networks (LNN)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/pranay-018/BreadcrumbsDeep-Learning-For-Remote-Sensing-LULC-Classification-Unveiling-Insights-With-SHAP.git
   cd BreadcrumbsDeep-Learning-For-Remote-Sensing-LULC-Classification-Unveiling-Insights-With-SHAP
## Acknowledgements

1.Sentinel-2 imagery
2.EuroSAT dataset
3.Keras and TensorFlow libraries
4.SHAP library
