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







