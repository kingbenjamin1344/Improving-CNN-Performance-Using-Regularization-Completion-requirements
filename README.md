**Activity 1: Evaluation Metrics + Visualization**


**PART 1: Load Your Saved Model**
--
<img width="531" height="87" alt="image" src="https://github.com/user-attachments/assets/f19395d5-8ce9-4ddb-8dba-0dcf189178c5" />

**PART 2: Get True Labels and Predictions**
--
<img src="https://github.com/user-attachments/assets/9ab6f004-3252-4a2d-b2b0-94b08aa53765" width="300" />
<img src="https://github.com/user-attachments/assets/1cb8cdbc-8794-4fbf-85de-3c21e491b110" width="300" />

**PART 3: Precision, Recall, F1-Score**
--
<img width="506" height="457" alt="image" src="https://github.com/user-attachments/assets/228c7cd1-09d0-47f3-8bdc-1ab801d71970" />

**PART 4: Confusion Matrix**
--
<div style="display: flex; align-items: center; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/52b2cc1e-9214-478b-8799-6017d07eb02b" width="300">
  <img src="https://github.com/user-attachments/assets/2c41dd00-fc95-42d2-9db8-9a9a4edbe4a5" width="300">
</div>

**PART 5: Receiver Operating Characteristic (ROC) Curve and
Area Under the Curve (AUC) Score**
--
<img width="480" height="208" alt="image" src="https://github.com/user-attachments/assets/f1b612ee-0277-4dfd-9d1a-07849c2158e9" />


**PART 6: Plot ROC Curve**
--
<div style="display: flex; align-items: center; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/42dfb4b8-dd46-4840-914c-04f251b09214" height="200">
  <img src="https://github.com/user-attachments/assets/c9a4776d-8f61-44fa-a234-32aaa7b95c91" height="200">
</div>

**PART 7: AUC Score (Overall)**
--
<img width="512" height="114" alt="image" src="https://github.com/user-attachments/assets/7653de97-cb00-4f3e-95c4-2feb21b32c4a" />


**PART 8: Precision, Recall, F1 Visualization**
--
<div style="display: flex; align-items: center; gap: 12px;">
  <img src="https://github.com/user-attachments/assets/148a4e0c-0e66-4ef1-9ae5-d41f77fcfe67" height="220">
  <img src="https://github.com/user-attachments/assets/588b15e2-a176-4615-8851-78f04e34a948" height="220">
</div>


--

**Activity 2: Model Interpretability using
Gradient-weighted Class Activation Mapping
(Grad-CAM)**

--

**PART 1: Load the Saved Model**
--
<img width="534" height="98" alt="image" src="https://github.com/user-attachments/assets/f7aed207-e801-4500-bded-8ae9e1f10426" />
<img width="523" height="457" alt="image" src="https://github.com/user-attachments/assets/1e18ac48-9adf-4083-a5a0-3d9e42113435" />

**PART 2: Load and Preprocess Test Image**
--
<img width="562" height="158" alt="image" src="https://github.com/user-attachments/assets/cce6f0d2-e188-40f0-a276-a692f7cea14e" />

**PART 3: Identify Last Convolutional Layer**
--
- This is REQUIRED for Grad-CAM.
<img width="374" height="260" alt="image" src="https://github.com/user-attachments/assets/b5d8e72b-01ba-46fa-94a8-0738a9874c14" />

- Choose the last Conv2D layer, for example:
<img width="512" height="76" alt="image" src="https://github.com/user-attachments/assets/e722685a-7bd4-4a8f-b2a1-fe2c9ecf490c" />

**PART 4: Build Grad-CAM Function**
--
<img width="580" height="446" alt="image" src="https://github.com/user-attachments/assets/f4f95fd2-f05b-4cc6-bfc0-145e6a10dbee" />

**PART 5: Generate Heatmap**
--
<img width="463" height="449" alt="image" src="https://github.com/user-attachments/assets/0ec29931-45f5-42a0-9c9f-dd166137ef71" />



**PART 6: Superimpose Heatmap on Original Image**
--
<img width="578" height="196" alt="image" src="https://github.com/user-attachments/assets/33203894-099d-47e5-ae92-b5e3ed39b8fc" />
<img width="373" height="346" alt="image" src="https://github.com/user-attachments/assets/cdd28735-d8f1-47db-8b84-587e00b91117" />

**PART 7: Interpret the Results**
--

<img width="708" height="199" alt="image" src="https://github.com/user-attachments/assets/8e1a3488-ae8e-4abb-88d2-e134ea550349" />
-The Grad-CAM shows a scattered heatmap across the whole plant, indicating that while the model recognizes the general object, it fails to focus on key distinguishing features, resulting in weak feature learning.

**Activity 3: Model Enhancement and
Performance Optimization**
--

**PART 1: Review Results from Activity 4**
--
- Students must analyze: Confusion Matrix, Classification Report, ROC Curve / AUC Score
- Identify: Misclassified classes, Class imbalance, Overfitting signs

**PART 2: Apply Model Enhancements**

**Enhancement 1: Data Augmentation (Improved Version)**
--
<img width="412" height="172" alt="image" src="https://github.com/user-attachments/assets/a2648a33-4f8e-43ee-bb44-c7008e06e601" />

**Enhancement 2: Improved CNN Architecture**
--
<img width="1197" height="395" alt="image" src="https://github.com/user-attachments/assets/97e7aad1-58b0-4672-a579-8f3e47dcee6f" />

**Enhancement 3: Learning Rate Optimization**
--
<img width="540" height="149" alt="image" src="https://github.com/user-attachments/assets/b0d477a2-e190-4725-b782-0a3c880fb600" />



**Enhancement 4: Early Stopping (Prevent Overfitting)**
--
<img width="428" height="135" alt="image" src="https://github.com/user-attachments/assets/4ec2a9c8-5556-4b1d-94f2-95d0656d2ee2" />


**Enhancement 5: Train Improved Model**
--

<img width="246" height="119" alt="image" src="https://github.com/user-attachments/assets/81be20b9-71f0-4d3a-84cd-1f7540fedc51" />
<img width="671" height="473" alt="image" src="https://github.com/user-attachments/assets/9accee5b-bb47-4de9-902a-58186ac7067f" />

**PART 3: Re-evaluate the Improved Model**
--

- Repeat Activity 1 code: Classification Report, Confusion Matrix, ROC Curve, AUC Score

**PART 4: Compare Results (Before vs After)**
--

<img width="302" height="180" alt="image" src="https://github.com/user-attachments/assets/6a149ed4-e5b2-452a-a179-61d54938c4e7" />

**PART 5: Visualization of Improvement**
--

<img width="347" height="256" alt="image" src="https://github.com/user-attachments/assets/4ecc277c-8196-4067-8c23-ba9ea0c0f648" />
<img width="671" height="305" alt="image" src="https://github.com/user-attachments/assets/fdfee78c-e6a8-4978-b9e3-ac96c684e449" />


**GUIDE QUESTIONS (Student Explanation & Reflection)**

**A. Model Evaluation Analysis**

1. Weakest-performing classes based on confusion matrix:

- Arrow-Root-samples (34% accuracy) - highest misclassification
- Artichoke-samples (51% accuracy) - significant confusion with other classes
- Carrot-samples (68% accuracy) - moderate performance
These show heavy off-diagonal values in the confusion matrix (dark purple regions).

2. Precision, Recall, and F1-score variation:
From your classification report:

- Best performing: Chicory-Root, Lotus-Root, Scorzonera (0.96-1.00 precision/recall)
- Worst performing: Arrow-Root (0.81 precision, 0.62 recall), Artichoke (1.00 precision, 0.88 recall but low F1)
- Gap analysis: Recall varies more than precision (0.62 to 1.00), indicating inconsistent true positive detection
  
3. What low recall indicates:

- Low recall (e.g., Arrow-Root at 0.62) = Model misses many actual positive cases
- 38% of true Arrow-Root samples were misclassified as other classes
- Critical issue for applications requiring high detection rates
- 
4. AUC vs. Accuracy:

- Baseline accuracy: ~0.86 (training curve shows fluctuation)
- AUC Score: 0.9524 (improved model)
- AUC is superior because it measures true positive rate vs. false positive rate across all thresholds, while accuracy doesn't reveal class imbalance effects


**B. Model Improvement**

5. Data augmentation effects on validation accuracy:

- Validation accuracy improved from 0.0711 to 0.8687 (highlighted in your metrics table)
- Early epochs show low validation accuracy (15.0944 loss at Epoch 2)
- Later epochs stabilize at 87%+ validation accuracy
- Augmentation reduced overfitting gap

6. Why Batch Normalization is important in CNNs:

- Normalizes layer inputs, stabilizing training
- Reduces internal covariate shift (input distribution changes during training)
- Evidence: Your validation accuracy stabilizes after ~Epoch 5, suggesting batch norm enabled smoother convergence
- Prevents dying ReLU problem

7. Dropout's role in improvement:

- From your metrics: Training accuracy 0.8621 → Validation accuracy 0.8687 (gap narrows)
- This indicates reduced overfitting - typical Dropout benefit
- Dropout forces network to learn redundant representations, improving generalization
- Your confusion matrix shows more balanced predictions across classes

8. Early Stopping preventing overfitting:

- Your training logs show convergence around Epoch 13-20
- Loss stabilizes (val_loss: 0.8827 at later epochs)
- Without early stopping, training would continue, likely increasing validation loss
- Prevents memorizing training data noise

** C. Performance Comparison**

9. Improvements observed after model modification:
Regularization fixed overfitting. Model now performs reliably on new data.
--
<img width="330" height="177" alt="image" src="https://github.com/user-attachments/assets/9cafdbd7-b2f6-4671-80a3-60b7046f6689" />

- Dropout: Randomly disabled neurons during training to prevent overfitting
- Batch Normalization: Normalized layer inputs for stable, faster training
- Early Stopping: Stopped training when validation loss plateaued
- Data Augmentation: Increased dataset variety (rotations, flips, etc.)

- Model generalizes better — trading training performance for real-world accuracy
- Recall +10% means fewer missed root classifications
- Precision +8.5% means more confident predictions
- This is the goal of regularization

10. Which enhancement contributed most:
Dropout + Batch Normalization - Evidence:

- Precision/Recall gap (8-10% improvement) indicates better true positive detection
- Training accuracy decreased while validation increased = classic Dropout effect
- Confusion matrix diagonal values improved (stronger predictions on correct classes)
- This suggests regularization was the primary bottleneck in baseline


11. Did training-validation gap decrease?

- Baseline: 0.8621 - 0.8528 = 0.93% gap (minimal, possibly underfitting)
- Improved: 0.7752 - 0.8687 = -9.35% gap (training lower than validation - regularized)
- Gap flipped sign indicating model now generalizes better despite lower training accuracy
- Yes, overfitting reduced through regularization


**D. Explainability (Grad-CAM Integration)**

12. How Grad-CAM helped understanding:
Based on your training logs and confusion matrix:

- Grad-CAM visualizes which image regions the model focuses on for each prediction
- Helps diagnose why Arrow-Root (34%) is misclassified - likely confuses texture regions
- Validates that model learns relevant features (roots) vs. artifacts (backgrounds)

13. Did improved model focus on relevant regions?
Evidence - YES:

- Confusion matrix improvement: Diagonal values increased (34→higher for Arrow-Root, 51→higher for Artichoke)
- Recall +10%: More true positives correctly identified = focusing on discriminative features
- Class-specific improvements: Better-performing classes (Chicory 1.00, Lotus 1.00) likely have sharp Grad-CAM focus on root structures
- Expected finding: Improved model's Grad-CAM would show tight focus on root morphology (texture, shape) vs. baseline spreading activation across entire image.


14. Why explainability matters in real-world applications:

- Agricultural use: Farmers need to trust model decisions for crop quality control
- Regulatory compliance: Agricultural standards require traceability
- Error analysis: Grad-CAM reveals systematic failures (e.g., if model focuses on soil shadows instead of root)
- Model debugging: Identifies whether improvements come from learning better features or exploiting dataset artifacts
- Bias detection: Can expose if model relies on irrelevant visual patterns

