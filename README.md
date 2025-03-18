# Volcanic Rock Classification using Machine Learning and Deep Learning

## Overview
This project involves analyzing geochemical data obtained from volcanic rock samples to classify their ages based on elemental compositions. The dataset includes measurements from two different analytical techniques:
- **Electron Microprobe Analysis (EMPA)**: Provides oxide and compound quantifications.
- **Laser Ablation Spectroscopy**: Offers broader elemental analysis.

The objective is to preprocess the data, visualize distributions, implement machine learning (ML) and deep learning (DL) classification models, and evaluate their performance.

## Features
- **Data Preprocessing**: Handling missing values, normalization, and feature selection.
- **Data Visualization**: Creating scatter plots, bar charts, pie charts, and heatmaps.
- **Machine Learning Models**: Implementing multiple classification models.
- **Deep Learning Model**: Applying a neural network for classification.
- **Model Performance Evaluation**: Using accuracy, precision, recall, and F1-score.

## Project Structure
```
|-- data/                          # Folder for dataset files
|-- notebooks/                     # Jupyter Notebooks for preprocessing, visualization, modeling
|   |-- data_preprocessing.ipynb   # Handling missing values, normalizing data
|   |-- data_visualization.ipynb   # Generating data plots
|   |-- ml_classification.ipynb    # Machine Learning models
|   |-- dl_classification.ipynb    # Deep Learning model
|-- src/                           # Python scripts for reproducibility
|   |-- preprocess.py              # Data preprocessing functions
|   |-- visualize.py               # Visualization functions
|   |-- ml_models.py               # Machine learning implementations
|   |-- dl_model.py                # Deep learning model
|-- README.md                      # Project documentation
|-- requirements.txt               # Python dependencies
```

## Installation
To set up the project, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/volcanic-rock-classification.git
   ```
2. Navigate into the project directory:
   ```bash
   cd volcanic-rock-classification
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook server:
   ```bash
   jupyter notebook
   ```

## Dataset
The dataset consists of chemical compositions of volcanic rocks, measured from different labs worldwide. It contains missing values in some Laser Ablation data, requiring preprocessing before analysis.

### EMPA Elements:
- NiO, F, CaO, SiO₂, Cr₂O₃, Na₂O, TiO₂, V₂O₃, MnO, MgO, ZnO, FeO, Al₂O₃, K₂O, Li₂O

### Laser Ablation Elements:
- Mg#, Li, Be, B, Mg, Si, Ca, Sc, Ti, V, Cr, Mn, Co, Ni, Cu, Rb, Sr, Y, Zr, Nb, Cs, Ba, La, Ce, Pr, Nd, Sm, Eu, Gd, Tb, Dy, Ho, Er, Tm, Yb, Lu, Hf, Ta, Pb, Th, U

## Usage
### 1. Data Preprocessing
- Load and clean the dataset.
- Handle missing values (imputation strategies).
- Normalize and prepare features for classification.

### 2. Visualization
- Generate distribution plots for key elements.
- Compare EMPA and Laser Ablation data characteristics.

### 3. Machine Learning Classification
- Train multiple classification models (e.g., Decision Trees, SVM, Random Forest).
- Compare performance metrics.

### 4. Deep Learning Classification
- Implement a neural network for rock age classification.
- Tune hyperparameters and evaluate results.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Contribution
This project is part of the **Python Programming for AI and Visualization** module. It is developed in a team-based setting, ensuring collaboration in code development and presentation.

## Submission Requirements
- **Code Submission**: Includes all notebooks and scripts.
- **Presentation**: A structured presentation covering:
  - Data preprocessing
  - Visualization
  - ML model implementation
  - DL model implementation

## License
This project is for academic purposes. Please adhere to university regulations regarding plagiarism and code originality.

## Contact
For any questions, reach out to the course instructor **Dr. Ali Salimian** or refer to the Moodle discussion forum.

---
**Author(s):** Your Team Name  
**Date:** March 2025

