# Smoke Detection with AI-based Sensor Fusion

## Project Overview
This project aims to develop a smart smoke detector using AI-based sensor fusion to avoid false positives. By leveraging data from multiple sensors, the model can make more accurate decisions about the presence of fire. The dataset used for this project was collected using IoT devices in various environments and fire scenarios.

## Features
- **Exploratory Data Analysis (EDA):**
  - Data cleaning, outlier treatment, and visualization.
  - Feature selection based on correlation analysis.
- **Model Building:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
- **Hyperparameter Tuning:**
  - Optimized Random Forest parameters for best performance.
- **Results Comparison:**
  - Logistic Regression: 89% accuracy.
  - SVM: 99.96% accuracy.
  - Random Forest: 100% accuracy (Winner).

## Dataset
- **Source:** [Kaggle Smoke Detection Dataset](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset/data)
- **Collected by:** Stefan Blattmann ([GitHub](https://github.com/Blatts01))

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/madaossama/AI-Powered_Smoke_Detection_System.git
   cd AI-Powered_Smoke_Detection_System
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook `AI-Powered_Smoke_Detection_System.ipynb`.
2. Follow the steps in the notebook to preprocess the data, train models, and evaluate results.

## Results
- **Logistic Regression:**
  - Advantages: Simple and memory-efficient.
  - Disadvantages: Assumes linear separability, leading to lower accuracy.
- **SVM:**
  - Advantages: High accuracy and handles non-linear features.
  - Disadvantages: Memory-intensive and time-consuming.
- **Random Forest:**
  - Advantages: Highest accuracy and less computationally intensive than SVM.
  - Disadvantages: Potential overfitting.



## Credits
- Dataset: [Kaggle Smoke Detection Dataset](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset/data)
- Project inspiration: [Real-time Smoke Detection with AI-based Sensor Fusion](https://www.hackster.io/stefanblattmann/real-time-smoke-detection-with-ai-based-sensor-fusion-1086e6)

## License
This project is licensed under the MIT License. See the LICENSE file for details.
