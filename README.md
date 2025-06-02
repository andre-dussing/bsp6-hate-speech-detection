# Hate Speech Detection

This repository contains code and notebooks for detecting hate speech using machine learning techniques. The project demonstrates data analysis, preprocessing, feature engineering, and model evaluation, all within Jupyter Notebooks.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Hate speech detection is a critical task in natural language processing (NLP) aimed at identifying and mitigating harmful online content. This project explores various approaches to classify text as hate speech or not, leveraging labeled datasets and popular machine learning algorithms.

## Project Structure

```
.
├── notebooks/           # Jupyter Notebooks for data exploration and modeling
├── data/                # Datasets (may be gitignored if too large)
├── README.md            # Project overview and instructions
├── requirements.txt     # Python dependencies (if applicable)
└── .gitignore
```

## Getting Started

## 💡 Overview

- **Objective**: Detect hate speech in social media comments using advanced NLP techniques.
- **Models Used**: Fine-tuned transformer models including BERT, HateBERT, and RoBERTa.
- **Dataset**: Reddit-based annotated datasets with varying preprocessing techniques.
- **Evaluation Metrics**: Accuracy, Precision, Recall, and F1-score.


## 🧰 Technologies Used

- Python
- HuggingFace Transformers
- PyTorch
- scikit-learn
- Optuna (for hyperparameter tuning)
- Pandas & NumPy



### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Recommended: create a virtual environment

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/andre-dussing/bsp6-hate-speech-detection.git
   cd bsp6-hate-speech-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

Open the notebooks in the `notebooks/` directory to explore the data and run the hate speech detection models.

## Data

- The datasets used for this project may be included in the `data/` directory or instructions provided in the notebooks for how to download them.
- Check the notebooks for dataset source and preprocessing steps.

## Results

The results of the experiments, including model performance metrics and visualizations, can be found within the notebooks.


## License

This project is licensed under the terms of the MIT License. See [LICENSE](LICENSE) for details.

## Contact

For questions, please contact [andre-dussing](https://github.com/andre-dussing).
