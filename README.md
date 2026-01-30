# Depression-Detection-System-Using-Machine-Learning-
A depression detection system was created using motion activity analysis, leveraging multiple machine learning models, including KNN, Random Forest, XGBoost, and LSTM neural networks to analyse wearable sensor activity patterns, with an ensemble approach achieving optimised classification accuracy.

## Project Overview
A machine learning-based system for detecting depression patterns by analysing motion activity data from wearable sensors. The system employs multiple algorithms to identify behavioural markers associated with depressive states.

## Key Features
- **Multi-Algorithm Approach**: Combines Random Forest, KNN, XGBoost, and LSTM models
- **Feature Engineering**: Extracts statistical patterns from hourly activity data
- **Ensemble Methods**: Uses voting classifiers and model averaging for improved accuracy
- **Participant-wise Validation**: Custom cross-validation to prevent data leakage
- **Comprehensive Evaluation**: Multiple performance metrics and feature importance analysis

## Model Performance
| Model | Accuracy | Notes |
|-------|----------|-------|
| Random Forest | 74.67% | Best individual performer |
| XGBoost | 72.93% | Gradient boosting approach |
| Voting Ensemble | 73.80% | Combined RF, KNN, XGBoost |
| K-Nearest Neighbors | 67.69% | Distance-based classification |
| LSTM | 65.07% | Time series neural network |
| **Final Ensemble (All Models)** | **73.80%** | **Best overall performance** |

## Requirements

To run the Jupyter Notebook and experiments, you’ll need:

- Python 3.x  
- Jupyter Notebook / Jupyter Lab  
- scikit-learn  
- pandas, numpy  
- matplotlib / seaborn for visualisation  
- TensorFlow or Keras (for LSTM)
