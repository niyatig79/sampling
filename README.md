# Sampling Assignment

## Overview
This repository demonstrates the application of various sampling techniques in machine learning. The primary focus is to balance datasets and evaluate their impact on model performance, making this a comprehensive learning experience in sampling methods.

## Features
- **Dataset Balancing**: Techniques to handle imbalanced datasets.
- **Sampling Methods**: Five sampling approaches including Random OverSampling, SMOTE, Random UnderSampling, Cluster Centroids, and SMOTETomek.
- **Model Evaluation**: Five machine learning models—Logistic Regression, Random Forest, SVM, Decision Tree, and K-Nearest Neighbors—tested for accuracy with each sampling method.

## Final Results
| Sampling Technique     | Logistic Regression | Random Forest | SVM      | Decision Tree | K-Nearest Neighbors |
|-------------------------|---------------------|---------------|----------|---------------|----------------------|
| Random Under-Sampling  | 0.827586            | 0.767241      | 0.987069 | 0.625000      | 0.689655            |
| Random Over-Sampling   | 0.922414            | 0.987069      | 0.706897 | 0.978448      | 0.969828            |
| SMOTE                  | 0.918103            | 0.987069      | 0.426724 | 0.689655      | 0.965517            |
| Cluster Centroids      | 0.482759            | 0.655172      | 0.668103 | 0.616379      | 0.508621            |
| SMOTETomek             | 0.918103            | 0.987069      | 0.521552 | 0.676724      | 0.969828            |

## Repository Structure
```
Sampling_Assignment/
├── Sampling_Assignment.ipynb  # Main notebook with implementation
├── Creditcard_data.csv        # Dataset (to be downloaded as per instructions)
├── Sampling_Assignment.pdf    # Assignment details and requirements
└── README.md                  # Project documentation
```

## Prerequisites
- Python 3.8+
- Libraries: Install all dependencies via `requirements.txt`

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/gatopotato/sampling_assignment.git
   cd sampling_assignment
   ```
3. Open the Jupyter notebook to explore and execute the implementation:
   ```bash
   jupyter notebook Sampling_Assignment.ipynb
   ```

## Learning Objectives
- Gain expertise in sampling techniques to handle imbalanced datasets.
- Understand the impact of sampling on different machine learning models.
- Learn to evaluate and document performance metrics effectively.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Author
- **Samkit Jaina**
- GitHub: [@gatopotato](https://github.com/gatopotato)
