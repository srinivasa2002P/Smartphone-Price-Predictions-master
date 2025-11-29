<html>
<body style="font-family: Arial, sans-serif; line-height: 1.6;">

<h1>📱 Smartphone Price Predictor</h1>
<p>
This is a machine learning project that predicts the price of a mobile phone based on its specifications. 
The data was scraped from the E-commerce website Flipkart, and the project is implemented using Streamlit.
</p>

<h2>🚀 Live App</h2>
<a href="https://smartphone-price-predictions.onrender.com" target="_blank">
Click here to open the deployed application
</a>

<hr>

<h2>📸 Application Screenshots</h2>

<h3>🔐 OTP Verification Page</h3>
<img src="C:\Users\91738\Desktop\Smartphone-Price-Predictions-master\Screenshot 2025-11-29 194220.png" width="100%" style="border-radius: 10px;">

<h3>📱 Mobile Price Prediction Interface</h3>
<img src="C:\Users\91738\Desktop\Smartphone-Price-Predictions-master\Screenshot 2025-11-29 194024.png" width="100%" style="border-radius: 10px;">

<h3>📊 Predicted Price Example</h3>
<img src="C:\Users\91738\Desktop\Smartphone-Price-Predictions-master\Screenshot 2025-11-29 194836.png" width="100%" style="border-radius: 10px;">

<hr>

<h2>⚙️ Installation</h2>
<p>Install all required libraries:</p>

<code>
pip install requests beautifulsoup4 pandas numpy scikit-learn flask streamlit
</code>

<h2>▶️ Usage</h2>
<p>To run the Streamlit application:</p>

<code>streamlit run app.py</code>

<p>This opens the app in your browser where you can enter specifications and get a predicted mobile price.</p>

<hr>

<h2>📂 Data</h2>
<p>
Raw dataset: <code>Flipkart_results(1).csv</code><br>
Preprocessed data: <code>mobile_df.pkl</code><br>
EDA Notebook: <code>EDA on mobile data.ipynb</code><br>
Model building notebook: <code>Models.ipynb</code><br>
Best ML pipeline saved as: <code>pipe.pkl</code>
</p>

<hr>

<h2>🧠 Model Selection</h2>
<p>The following models were evaluated:</p>
<ul>
    <li>Linear Regression</li>
    <li>Ridge</li>
    <li>Lasso</li>
    <li>KNN Regressor</li>
    <li>SVM</li>
    <li>Decision Trees</li>
    <li>Extra Trees</li>
    <li>Random Forest</li>
    <li>AdaBoost</li>
    <li>XGBoost</li>
    <li>Voting Regressor</li>
    <li>Stacking Regressor</li>
</ul>

<p>
⭐ <b>Best Model: Random Forest</b><br>
🎯 <b>Accuracy: 92%</b>
</p>

<hr>

<h2>🤝 Contributing</h2>
<p>Feel free to submit issues or pull requests on GitHub.</p>

<h2>🏁 Conclusion</h2>
<p>
Our mobile price predictor uses machine learning to estimate the price of a smartphone based on its features. 
The project includes web scraping, data preprocessing, ML modeling, and UI deployment via Streamlit.
With an accuracy of 92%, the Random Forest model performs best.
</p>

<p>This project can be expanded with more data sources, more models, and additional UI features.</p>

<p>Thank you for checking out this project! 😊</p>

</body>
</html>
