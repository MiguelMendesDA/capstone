🧠 Price Forecasting API (Docker)

API for competitive price forecasting, developed with Python, Flask. Designed to meet the needs of **Retailz**, the solution provides real-time forecasts of the final selling prices of two strategic competitors, enabling faster and smarter business decisions.

This project was developed as the **final capstone project** of the **Data Science course at Lisbon Data Science Academy**.


📌 Introduction

Retailz, a growing retail chain, identified the need to enhance its pricing intelligence to remain competitive in a highly dynamic market. This project was developed to address two main strategic objectives:

1. 📉 Historical Analysis
   
By processing competitor price time series, we aim to:

 - Understand pricing behavior patterns over time;

 - Identify recurring discounts and promotional campaigns;

 - Assess how competitiveness varies across different product categories;

 - Detect possible price reaction behavior between competitors (e.g., one competitor lowering prices after another);

 - Compare competitors’ average price levels with those practiced by Retailz.

These analyses provide valuable insights to adjust strategies by category or seasonality.

2. 🔮 Price Forecasting via API
   
The second objective was to develop a robust, scalable, and integrable forecasting solution:

 - Predict the final selling price (PVP) of two competitors based on a SKU and a future date;

 - Deliver reliable forecasts across multiple categories with seasonal and market variations;

 - Make the model available through a REST API, fully integrable with Retailz’s internal systems;

 - Allow registering actual prices later, enabling accuracy monitoring.

💼 Business Rationale

Anticipating competitor behavior is essential for Retailz to remain competitive without compromising margins. With this API, the pricing team can:

 - Simulate future scenarios;

 - Adjust prices strategically;

 - Respond more quickly to market movements;

 - Manage margins with greater control.



📦 Project Structure

├── app.py                  # Flask API with REST endpoints

├── download_models.py      # Script to download pre-trained models from Hugging Face

├── Dockerfile              # Image definition for build and execution with Docker

├── requirements.txt        # Python dependencies list

├── EDA.ipynb               # Exploratory Data Analysis and feature generation

├── model.ipynb             # Model training, tuning, and export

├── models/                 # (generated) Stores the downloaded .pkl files

├── presentation/           # Project presentation materials

└── reports/                # Generated reports and analysis outputs

👨‍💻 Author

Miguel Mendes

📧 miguelmendesdataanalyst@gmail.com

🔗 www.linkedin.com/in/miguelmendes-healthcare-dataanalyst
