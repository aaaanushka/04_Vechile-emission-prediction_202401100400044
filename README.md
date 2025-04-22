# 04_Vechile-emission-prediction_202401100400044
 Classify Vehicles Based on Engine Emissions This project uses machine learning to classify vehicles into emission categories (A, B, C) based on their engine and fuel characteristics. It aims to support environmental compliance and vehicle assessment by predicting a vehicle's emission class from its technical specs.  
  Classify Vehicles Based on Engine Emissions
This project uses machine learning to classify vehicles into emission categories (A, B, C) based on their engine and fuel characteristics. It aims to support environmental compliance and vehicle assessment by predicting a vehicle's emission class from its technical specs.

The dataset includes 100 samples, each containing:

Engine Size

Fuel Type (Petrol, Diesel, Electric)

CO₂ Emissions

🧠 Model
A Random Forest Classifier was chosen for its ability to handle both numerical and categorical data and reduce overfitting. The dataset was split into training (80%) and testing (20%) sets. The model was trained using Scikit-learn and evaluated with classification metrics like accuracy, precision, recall, and F1-score.

⚙️ Tools & Libraries
Python

Pandas & NumPy

Scikit-learn

(Optional) Seaborn/Matplotlib for visualization

✅ Results
The model showed strong performance, accurately classifying vehicles into emission categories. Feature importance analysis showed that CO₂ emissions and engine size were the most influential predictors.

This project demonstrates how machine learning can assist in environmental data analysis and classification tasks.
