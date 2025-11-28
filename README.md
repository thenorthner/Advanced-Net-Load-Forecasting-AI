#  Advanced Net Load Forecasting AI

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Model-XGBoost-orange)
![Frontend](https://img.shields.io/badge/Frontend-Gradio-cyan)
![Status](https://img.shields.io/badge/Status-Completed-success)

> **A Smart Grid Management System that predicts Net Load by analysing Solar Generation, Weather Conditions, and Historical Consumption Patterns.**

REPORT : https://drive.google.com/file/d/14O9umxJLR7923XFyVpy5rpWXCDfcSV-t/view?usp=sharing
---

##  Dashboard Preview

###  The "Elite" Control Room (Gradio Interface)
<img width="1364" height="767" alt="image" src="https://github.com/user-attachments/assets/9f5766e2-ff7d-4057-bff5-f5d6cd5d4142" />

*Real-time prediction showing Grid Status, Solar Generation, and Consumption.*

###  Solar Generation Heatmap
<img width="1432" height="757" alt="image" src="https://github.com/user-attachments/assets/c626757d-72d5-436c-b3c0-6ab38c33eae6" />

*Yearly solar intensity analysis showing the "Golden Band" of peak generation.*

---

##  The Problem: "The Duck Curve"

<img width="800" height="450" alt="newplot (1)" src="https://github.com/user-attachments/assets/0ff89a0c-e862-4fc8-bc85-f9203ba6dcf8" />

With the rise of renewable energy, grid operators face a massive challenge:
1.  **Mid-Day Dip:** Solar generation peaks at noon, causing Net Load to drop drastically (sometimes becoming negative).
2.  **Evening Ramp:** As the sun sets and people return home, demand skyrockets while solar output hits zero.

This project uses **Machine Learning (XGBoost)** to forecast these fluctuations with **98%+ accuracy**, helping in efficient Grid Dispatch Planning.

---

##  Key Features
* ** Advanced ML Engine:** Powered by `XGBoost Regressor` optimised for time-series forecasting.
* ** Physics-Aware Modelling:** Features include Irradiation, Module Temperature, and Ambient Temperature interactions.
* ** Interactive Dashboard:** Built with `Gradio` & `Plotly` for real-time scenario simulation (Dark Theme UI).
* ** Dynamic Demand Simulation:** Synthesised consumption patterns accounting for Morning/Evening peaks.
* ** Explainable AI:** Includes SHAP analysis to understand feature impact.

---

##  Tech Stack
* **Language:** Python 
* **Machine Learning:** XGBoost, Scikit-Learn
* **Data Processing:** Pandas, NumPy
* **Visualisation:** Plotly, Seaborn, Matplotlib
* **Frontend:** Gradio (with Custom CSS)

## Visualisations: 
<img width="1015" height="528" alt="image" src="https://github.com/user-attachments/assets/270236c3-38b1-4dda-b5ab-39b47f5c6250" />

<img width="1015" height="528" alt="image" src="https://github.com/user-attachments/assets/86cce9b6-1b38-418b-bc6d-61a2c52d97a5" />

<img width="1316" height="574" alt="image" src="https://github.com/user-attachments/assets/1ec86dd4-2db6-4865-adb0-62fe7fb727ff" />

<img width="928" height="728" alt="image" src="https://github.com/user-attachments/assets/db51955a-161b-42e7-94bc-53f563cbd4ef" />

<img width="1040" height="574" alt="image" src="https://github.com/user-attachments/assets/7d313a96-65ff-41b1-83e1-1d6f60539573" />

<img width="1203" height="733" alt="image" src="https://github.com/user-attachments/assets/92a98156-c5dc-411f-afce-d06439a45982" />

<img width="1432" height="757" alt="image" src="https://github.com/user-attachments/assets/9db4ccba-9708-4e09-ade9-6f5363acb634" />

<img width="914" height="579" alt="image" src="https://github.com/user-attachments/assets/60bf3bc9-e1bf-4ba8-96f9-693d9f8fea2b" />

<img width="1069" height="579" alt="image" src="https://github.com/user-attachments/assets/2f7df265-84d2-4206-980f-19ced19b59cb" />

<img width="748" height="374" alt="image" src="https://github.com/user-attachments/assets/3996f164-160f-4d8a-abef-c17332389981" />

<img width="706" height="465" alt="image" src="https://github.com/user-attachments/assets/2d07b610-c33a-40bc-a5b2-3d426fc0577f" />


 Model Performance
Algorithm: XGBoost Regressor

R² Score: 0.9836 (98.36% Accuracy)

Key Insight: The model successfully captures the inverse relationship between high Irradiation and Net Load drops.










