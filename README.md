# DataScienceHeartDiseaseAssignment
Heart Disease


Let's go through the 14 attributes, focusing on understanding what they mean in the context of heart disease diagnosis:

1. **Chest Pain Type (cp)**:
   - This attribute represents the type of chest pain the patient experiences.
   - **Types**:
     - **1: Typical Angina** - Predictable chest pain typically triggered by stress or exertion.
     - **2: Atypical Angina** - Chest pain that doesn’t fit the typical pattern, less predictable.
     - **3: Non-Anginal Pain** - Chest pain that isn’t related to heart conditions.
     - **4: Asymptomatic** - No chest pain.

2. **Serum Cholesterol (chol)**:
   - **Cholesterol** is a type of fat (lipid) in your blood.
   - High levels of cholesterol can lead to the buildup of plaque in your arteries, which can increase the risk of heart disease.

3. **Fasting Blood Sugar (fbs)**:
   - This measures blood sugar levels after fasting (usually overnight before the test).
   - **Fasting Blood Sugar > 120 mg/dl** indicates high blood sugar, which can be a sign of diabetes or a risk factor for heart disease.

4. **Electrocardiogram (restecg)**:
   - An **Electrocardiogram (ECG or EKG)** is a test that measures the electrical activity of the heart to show whether or not it is working normally.
   - It helps in detecting heart problems like arrhythmias, heart attacks, or other conditions.

5. **Maximum Heart Rate Achieved (thalach)**:
   - **Thalach** stands for the maximum heart rate a person can achieve during exercise, which can indicate the heart’s capacity to handle stress.

6. **Exercise-Induced Angina (exang)**:
   - **Angina** is chest pain caused by reduced blood flow to the heart.
   - **Exercise-Induced Angina** means that this pain occurs during physical exertion, suggesting that the heart may not be getting enough oxygen.

7. **ST Depression Induced by Exercise (oldpeak)**:
   - **ST Segment** refers to a section on the ECG.
   - **ST Depression** occurs when this segment dips below the baseline, which can indicate reduced blood flow to the heart muscle during exercise.
   - This **"depression"** is not related to mood but rather to how the heart functions under stress.

8. **Slope of Peak Exercise ST Segment (slope)**:
   - The **slope** of the ST segment during peak exercise can indicate the heart's health:
     - **Upsloping**: Often normal.
     - **Flat**: Possible concern.
     - **Downsloping**: More serious, indicating heart disease.

9. **Number of Major Vessels Colored by Fluoroscopy (ca)**:
   - **Fluoroscopy** is a type of medical imaging that shows a continuous X-ray image on a monitor.
   - **Ca** refers to the number of major coronary arteries that are visible (or blocked) when injected with a contrast dye. This helps determine the extent of coronary artery disease.

10. **Thallium Stress Test Result (thal)**:
    - **Thallium** is a radioactive substance used in stress tests to visualize blood flow in the heart.
    - **Results**:
      - **3: Normal** - Normal blood flow.
      - **6: Fixed Defect** - An area of the heart muscle that does not receive blood at all, even at rest.
      - **7: Reversible Defect** - An area that doesn't receive enough blood during exercise but is okay at rest.

11. **Target (num)**:
    - This is the **diagnosis of heart disease**, where:
      - **0** indicates no significant heart disease (less than 50% narrowing of any major blood vessel).
      - **1-4** indicate varying degrees of heart disease (greater than 50% narrowing).

These attributes collectively help in predicting the presence and severity of heart disease in patients based on various clinical factors.
