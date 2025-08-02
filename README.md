# glycemic-reponse-prediction
# Project Objectives
This project models the glycemic response to local meals (Dambu) and predicts diabetes risk using AI. It also simulates the progression of antibiotic resistance in bacterial populations. It highlights the role of AI in preventive healthcare and public health research.
# Project Overview
This project is part of a research-based pilot focused on improving preventive healthcare. The aim is to:
Predict the glycemic index of local meals (Dambu) using their nutritional composition and sensory scores.
Predict diabetes risk by modeling glucose response, especially blood glucose level after 2 hours of meal intake (Glucose_120min_mmol_L).
Simulate antibiotic resistance in bacterial populations to show how resistance can spread over time.
The work reflects Otondo's commitment to using data to support healthier choices and long-term well-being.

**Model 1: Predicting Glycemic Index**
Target Variable: Calculated_Glycemic_Index_Percent
Features Used:
Carb_Percent, Protein_Percent, Fat_Percent, Fiber_Percent (Nutritional content)
Flavor, Taste, Texture, Consistency, Color (Sensory evaluations)
Model Type: RandomReggressor
**Performance:**
Mean Squared Error (MSE): 1.68
R² Score: 0.62
This model helps us understand how the makeup of food affects its glycemic index — useful for meal planning and health monitoring.

**Model 2: Predicting Glucose Response / Diabetes Risk**
Target Variable: Glucose_120min_mmol_L
This variable represents the blood sugar level 2 hours after eating. It's a standard way to detect impaired glucose tolerance or early diabetes signs.
Features Used:
Age, Portion_Size_g, Boiled, Carb_Percent, Fat_Percent, Fiber_Percent, Dambu_Type and Gender.
Model Type: Linear Regression

**Performance:**
Mean Square Error(MSE): 0.01
R-Square Error: 0.98

This model helps estimate how a person's body reacts to certain foods, making it easier to catch warning signs early.

**Antibiotic Resistance Simulation**
In addition to modeling food and glucose, the project also simulates how bacteria might become resistant to antibiotics. The simulation shows how resistance builds over time under different treatment conditions. It's a simple way to raise awareness about overuse of antibiotics.

**Tools Used**
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

**Conclusion**
This project brings together food science, health, and biology to support smart health decisions. By predicting both glycemic index and glucose response, and simulating antibiotic resistance, it helps highlight small changes that can make a big difference in health outcomes.

