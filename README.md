# End-to-End-Learning-System-with-Regularization-and-Validation-Predicting-1s-vs.-Not-1s
# **Experiment Section**  
  - Normalization and feature selection (256 → 3 features)  
  - Training/test dataset features: **intensity** and **symmetry**  
  - Regularized linear regression with varying **λ**  
  - Analysis of **overfitting vs underfitting**  
  - Visualization of classification boundaries
    
# Key Observations
- Initial increase of λ reduces **overfitting** and improves generalization.  
- Beyond a threshold, higher λ introduces **bias** and leads to underfitting.  
- Cross-validation error (ECV) follows the **bias-variance tradeoff** pattern.  
- Feature selection (intensity & symmetry) reduces dimensionality while preserving useful signals.
-
# Tools & Environment
- **Google Colab / Python 3.x**  
- Libraries:
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
# Learning Outcomes
- Applied **regularization** to mitigate overfitting.  
- Understood **cross-validation trends** with varying λ.  
- Learned the importance of **feature selection & dimensionality reduction**.  
- Explored **bias-variance trade-off** in practical ML experiments. 
