# Real-Time-AI-Weather-Prediction-System
🚀 
This project demonstrates how Large Language Models (LLMs) can be applied to meteorology by combining geographic analysis, seasonal patterns, and atmospheric science principles into intelligent forecasts.

**Sample Result**

<img width="1839" height="722" alt="Screenshot 2025-08-24 205110" src="https://github.com/user-attachments/assets/fe0b83d9-08b9-4a6a-90a7-23c66af5426e" />


<img width="1857" height="739" alt="Screenshot 2025-08-24 205206" src="https://github.com/user-attachments/assets/e7bab2fd-6192-4f07-a673-8d3ffc95b360" />


<img width="1848" height="654" alt="Screenshot 2025-08-24 205222" src="https://github.com/user-attachments/assets/c77ebf1e-79c2-40d6-ae49-671e07c6d554" />




✨ Features

📍 Location Intelligence – Retrieves geographic, climate zone, and seasonal details for better accuracy.

⏳ Flexible Forecasting – Get predictions for the next N hours (default: 24).

🆚 Location Comparison – Compare weather between two cities with pros/cons for activities.

🔄 Continuous Monitoring – Auto-refresh forecasts at set intervals (e.g., every 60 min).

🛡️ Robust Error Handling – Handles API issues, rate limits, and invalid JSON gracefully.

🎯 Practical Insights – Clothing advice, travel tips, agricultural considerations, and health warnings.

🚀 Tech Stack

Python 3

OpenRouter API (DeepSeek model)

Datetime & JSON utilities for forecast processing

CLI-based interface (user-friendly with emoji prompts 🎉)

📦 Installation
# Clone the repo
git clone https://github.com/yourusername/ai-weather-predictor.git
cd ai-weather-predictor

# Install dependencies
pip install -r requirements.txt

🔑 Setup API Key

Get your free API key from OpenRouter
.

Set it as an environment variable:

export OPENROUTER_API_KEY="your_api_key_here"   # Linux/Mac
setx OPENROUTER_API_KEY "your_api_key_here"    # Windows


The script will automatically use your key.

▶️ Usage

Run the program:

python ai_weather.py


Choose a mode:
1️⃣ Single location forecast
2️⃣ Compare two locations
3️⃣ Continuous monitoring

📌 Example

Single Forecast (London, 24h ahead):

🌤️ Generating AI weather prediction for London...
✅ AI Weather Prediction generated successfully!

📋 AI WEATHER PREDICTION FOR LONDON:
------------------------------------------------------------
1. Current Weather: 16°C, Cloudy, 65% Humidity
2. 24h Forecast: Light rain expected overnight, winds 15km/h
3. Warnings: Possible fog tomorrow morning
4. Recommendations: Carry umbrella, avoid early morning travel

🌍 Future Enhancements

🔗 Integrate with real weather APIs (Open-Meteo, OpenWeatherMap).

📊 Add visualizations (matplotlib/plotly) for hourly forecast trends.

🌐 Build a Streamlit web app with live charts and alerts.

🗄️ Store predictions in a database for historical trend analysis.

🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.
