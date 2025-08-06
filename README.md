# MY_MTECH_PROJECT
_This project was done to predict the churn rate in the telecom domain, using the deep learning model._
**Project Files**
DATASET.csv: Preprocessed dataset containing telecom customer features and churn labels.

EXISTING.ipynb: Implementation of the baseline churn prediction model using ConvLSTM with SMOTE for class imbalance handling.

PROPOSED_WITHOUT_ATTENTION.ipynb: Proposed model using ConvLSTM and GAN-based synthetic data generation, without attention mechanism.

PROPOSED_WITH_ATTENTION.ipynb: Enhanced version of the proposed model integrating an optional attention mechanism to improve feature learning.

**Existing System**
The existing churn prediction system utilizes a ConvLSTM architecture to model temporal patterns in customer behavior. To address the issue of class imbalance, the SMOTE (Synthetic Minority Oversampling TEchnique) method was applied during preprocessing. While this approach improved prediction to a certain extent, limitations remained in capturing complex data distributions.

**Proposed System**
The proposed solution enhances the existing pipeline by replacing SMOTE with a GAN (Generative Adversarial Network) to generate more realistic synthetic samples for the minority class. This GAN-based approach significantly improves the model's ability to learn from imbalanced data. Additionally, an attention mechanism is optionally integrated into the ConvLSTM model to better focus on relevant temporal features, further boosting the model's performance.

**Key Contributions**
Comparison between traditional oversampling SMOTE and GAN-based data augmentation.

Use of ConvLSTM to capture temporal dependencies in churn-related features.

Optional attention module to enhance feature discrimination in the proposed model.
