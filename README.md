This Python script fetches the weather forecast for the next few hours and sends an SMS notification if rain is expected. It uses the OpenWeatherMap API to get the weather data and the Twilio API to send the SMS.


Prerequisites

OpenWeatherMap API Key: You need to sign up at OpenWeatherMap to get an API 

key.Twilio Account: You need a Twilio account with a verified phone number. Sign up at Twilio to get your account_sid and auth_token.

Installation

Install the required Python packages:

pip install requests twilio

Replace the placeholders in the script with your actual API keys and phone numbers.


Usage

Replace the placeholders (__YOUR_OWM_API_KEY__, __YOUR_TWILIO_ACCOUNT_ID__, __YOUR_TWILIO_AUTH_TOKEN__, YOUR TWILIO VIRTUAL NUMBER, YOUR TWILIO VERIFIED REAL NUMBER) with your actual values.

Run the script using a Python interpreter:

python weather_notification.py
