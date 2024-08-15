# DataScienceHeartDiseaseAssignment
Heart Disease

## Heart Disease Attribute Breakdown
  !- Generated to understand variables -!
These attributes are pivotal in evaluating the risk and presence of heart disease in patients.

1. **Age**:
   - This attribute represents the patient’s age in years.
   - Age is a critical factor in heart disease risk, with older individuals generally at higher risk.

2. **Sex (gender)**:
   - This denotes the patient’s gender (1 = male, 0 = female).
   - Gender plays a role in heart disease risk, with men typically at higher risk at a younger age compared to women.

3. **Chest Pain Type (cp)**:
   - This attribute categorizes the type of chest pain the patient experiences, which is crucial for diagnosing heart conditions.
   - **Types**:
     - **1: Typical Angina** - Predictable chest pain triggered by stress or exertion.
     - **2: Atypical Angina** - Chest pain that doesn’t follow the typical pattern.
     - **3: Non-Anginal Pain** - Chest pain unrelated to heart conditions.
     - **4: Asymptomatic** - No chest pain present.

4. **Resting Blood Pressure (trestbps)**:
   - **Resting Blood Pressure** is measured in mm Hg at the time of admission.
   - High blood pressure (hypertension) is a significant risk factor for heart disease.

5. **Serum Cholesterol (chol)**:
   - **Cholesterol** refers to the total serum cholesterol level in mg/dl.
   - Elevated cholesterol can lead to plaque buildup in arteries, increasing heart disease risk.

6. **Fasting Blood Sugar (fbs)**:
   - This measures blood sugar levels after fasting (typically overnight before the test).
   - **Fasting Blood Sugar > 120 mg/dl** is an indicator of high blood sugar, which could signal diabetes, a key risk factor for heart disease.

7. **Resting Electrocardiogram (restecg)**:
   - An **Electrocardiogram (ECG or EKG)** measures the electrical activity of the heart, providing information about heart rhythm and potential abnormalities.
   - **Values**:
     - **0: Normal**.
     - **1: ST-T wave abnormality** (which could indicate heart issues).
     - **2: Left ventricular hypertrophy**.

8. **Maximum Heart Rate Achieved (thalach)**:
   - **Thalach** refers to the highest heart rate a patient achieves during exercise, indicating the heart’s ability to function under stress.

9. **Exercise-Induced Angina (exang)**:
   - **Angina** is chest pain due to reduced blood flow to the heart.
   - **Exercise-Induced Angina** indicates whether this pain occurs during physical exertion, suggesting that the heart may not be receiving enough oxygen during exercise.

10. **ST Depression Induced by Exercise (oldpeak)**:
    - **ST Segment** refers to a section on an ECG.
    - **ST Depression** indicates a dip below the baseline, suggesting reduced blood flow to the heart muscle during exercise.

11. **Slope of Peak Exercise ST Segment (slope)**:
    - This represents the slope of the ST segment during peak exercise, indicating the heart’s condition.
    - **Types**:
      - **1: Upsloping** (usually normal).
      - **2: Flat** (possible concern).
      - **3: Downsloping** (more likely to indicate heart disease).

12. **Number of Major Vessels Colored by Fluoroscopy (ca)**:
    - **Fluoroscopy** is an imaging technique that provides real-time X-ray images.
    - The **ca** attribute represents the number of major coronary arteries (0-3) that show blockages when highlighted with contrast dye, helping to assess the extent of coronary artery disease.

13. **Thallium Stress Test Result (thal)**:
    - **Thallium** is a radioactive tracer used in stress tests to visualize blood flow in the heart.
    - **Results**:
      - **3: Normal** - Normal blood flow.
      - **6: Fixed Defect** - An area with permanently reduced blood flow.
      - **7: Reversible Defect** - An area with reduced blood flow during exercise but normal flow at rest.

14. **Target (num)**:
    - This is the **diagnosis of heart disease**:
      - **0**: No significant heart disease (less than 50% narrowing of any major coronary artery).
      - **1-4**: Presence of heart disease, with varying degrees of severity (greater than 50% narrowing).

These 14 attributes are key to predicting and diagnosing heart disease, offering a comprehensive assessment of a patient’s cardiovascular health.
