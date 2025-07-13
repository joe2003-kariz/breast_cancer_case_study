
# Interpretable Breast Cancer Prediction Using Machine Learning

## Project Overview

This project applies **machine learning and explainable AI (XAI)** techniques to predict breast cancer diagnoses (malignant vs. benign) using the **Breast Cancer Wisconsin (Diagnostic) dataset**. The model emphasizes not just high accuracy, but also **transparency and interpretability**, making it suitable for real-world clinical decision support.

The project was developed as part of the **DLBDSME01 – Model Engineering Case Study** coursework.

## Objectives

- Build a **binary classification model** for breast cancer prediction.
- Achieve an **F1 score ≥ 0.95** while minimizing false negatives.
- Integrate **SHAP (SHapley Additive Explanations)** for local and global interpretability.
- Propose a **clinically relevant GUI interface** for model deployment.
- Provide full reproducibility through transparent code and documentation.

## Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **Features:** 30 numerical features describing cell nucleus properties  
- **Samples:** 569 observations  
- **Labels:** Malignant (1) or Benign (0)

## Project Structure

| Folder/File | Description |
|-------------|-------------|
| `notebook.ipynb` | Full Jupyter Notebook (data preprocessing, modeling, SHAP analysis) |
| `scripts/` | Optional: Python scripts for modular execution |
| `data/` | Dataset CSV files (if permitted) |
| `README.md` | Project overview and instructions |
| `report.docx` | Final case study document (Word format) |
| `images/` | SHAP plots, confusion matrices, GUI mockups |

## Methodology

The project follows the **CRISP-DM** framework:

1. **Business Understanding:** Identify the clinical need for interpretable AI.
2. **Data Understanding:** Explore and visualize data distributions and correlations.
3. **Data Preparation:** Clean, encode, and normalize the dataset.
4. **Modeling:** Use Random Forest, Decision Trees, and Logistic Regression.
5. **Evaluation:** Assess model performance using F1-score, confusion matrix, and ROC.
6. **Interpretability:** Apply SHAP to explain model predictions.
7. **Deployment Proposal:** Design GUI components for clinical integration.

## Key Results

- **F1 Score:** 0.96  
- **False Negatives:** 3 (after threshold tuning and SHAP review)  
- **Explainability:** Integrated SHAP visualizations for feature contribution analysis.

## Usage Instructions

### Run Locally

1. Clone the repository:

```bash
git clone https://github.com/yourusername/breast-cancer-case-study.git
cd breast-cancer-case-study
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook notebook.ipynb
```

## View Online

- **GitHub Notebook Link:**  
[View on GitHub](https://github.com/joe2003-kariz/breast_cancer_case_study.git)

## Visual Aids

| Visual | Link |
|---------|------|
| SHAP Summary Plot | [SHAP Docs](https://github.com/slundberg/shap#visualizations) |
| GUI Mockup (Wireframe) | [UI8 Medical Dashboard](https://ui8.net/ugurates/products/medical-dashboard-ui-kit) |
| Confusion Matrix Example | [Scikit-learn Example](https://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html) |

## References

- Géron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*.  
- Lundberg, S. M., & Lee, S.-I. (2017). *A Unified Approach to Interpreting Model Predictions*.  
- Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). *“Why Should I Trust You?”*  
- Samek, W., Wiegand, T., & Müller, K.-R. (2017). *Explainable Artificial Intelligence*.

## License

This project is for **educational and academic purposes only**. No clinical deployment is implied.

