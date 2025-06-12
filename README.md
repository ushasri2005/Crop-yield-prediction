🌾 Crop Yield Prediction using AI/ML

This project uses AI/ML and deep learning concepts to predict crop yield based on environmental, regional, and agricultural input features. It also performs clustering of farming patterns using KMeans and regression analysis for prediction.

📁 Dataset

- Input CSV: `crop.csv`
- Columns include: Crop, Season, State, Crop_Year, Area, Production, Annual Rainfall, Fertilizer, Pesticide, Yield

📊 Techniques Used

- Data Preprocessing (Cleaning, Encoding, Normalization)
- Outlier Detection (Z-score method)
- Clustering (KMeans + Elbow Method)
- Regression (Linear Regression)
- Visualization (Matplotlib, Seaborn)

⚙️ Requirements

- Python (Colab environment preferred)
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

🚀 How to Run

1. Upload `crop.csv` when prompted in Colab.
2. Run the entire notebook.
3. Use the function `predict_yield(user_input)` to make predictions with custom inputs.

🧠 Model Performance

- Mean Squared Error (MSE): _(value prints at runtime)_
- R² Score: _(value prints at runtime)_