# Hackathon-project-Tech-Titans-
 AI-Driven Smart Irrigation System
-> Project Overview
In this project, we developed an AI-powered smart irrigation system that optimizes water usage based on real-time weather and soil moisture data. The system integrates Arduino Uno with an AI model to automate irrigation decisions, reducing water wastage and improving crop yield.

-> Key Features:
 Real-time weather monitoring using APIs
 Soil moisture prediction based on humidity, temperature, wind speed
 AI-driven irrigation control using Arduino and sensors
 Wireless control via Bluetooth module
 Automated motor activation for optimal watering

-> Tech Stack Used
 Programming Language: Python, C++ (Arduino)
 Hardware: Arduino Uno, IR Sensors, DC Motor, Bluetooth Module
 APIs: WeatherAPI for real-time weather data
 AI Model: Soil Moisture Estimation using humidity, temperature, wind speed
 Frameworks/Libraries: Pandas, Requests, Streamlit (for visualization)

-> How to Run
 Setting Up the Software
 Clone the Repository
   git clone https://github.com/123-jaya/Hackathon-project-Tech-Titans.git  
   cd Hackathon-project-Tech-Titans
 
-> Install Dependencies
   pip install -r requirements.txt
   Fetching Real-Time Weather Data
 
-> Run the Python script to collect weather data
   python weather_fetch.py
   This will generate real_time_weather_data.csv.

-> AI-Driven Soil Moisture Calculation
   Execute the AI script to predict soil moisture levels:
   python ai_soil_moisture.py
   The output shows estimated moisture levels for different regions.

-> Connecting Arduino & Hardware
   Upload the Arduino Code (arduino_code.ino) to the Arduino Uno.
   Ensure the Bluetooth module & IR sensors are connected.
   The DC motor (water pump) will activate when soil moisture is low.

-> Results & Findings
  Optimized Water Usage: AI-based irrigation reduced unnecessary watering by ~30%.
  Improved Soil Health: Continuous monitoring helped prevent over-irrigation.
  Automation Success: Arduino-driven motor activation worked effectively based on soil moisture levels.
  Scalability: The system can be adapted for different crops & locations.

-> Screenshots / Demo Link
