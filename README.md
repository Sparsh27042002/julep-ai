This Streamlit app generates a personalized, one-day foodie tour for any city you enter! Based on real-time weather data and local cuisine, it recommends indoor or outdoor dining, three iconic dishes, and top-rated restaurants serving them. Perfect for travelers, food bloggers, or locals exploring their own city!

✨ Features
🔍 City Input: User provides the name of the city they want to explore.

🌦️ Weather Detection: Real-time weather data via OpenWeatherMap API to suggest indoor or outdoor dining.

🍜 Iconic Dishes: Picks 3 iconic local dishes (custom curated per city).

🏆 Top Restaurants: Uses the Yelp API to find top-rated restaurants for those dishes.

📖 Foodie Narrative: Builds a delightful narrative around breakfast, lunch, and dinner, factoring in local weather and dish availability.

🚀 How to Run
Install dependencies:
pip install streamlit requests python-dotenv
Add your API keys in a .env file:

OPENWEATHER_API_KEY=your_openweather_key
YELP_API_KEY=your_yelp_key
Run the app:
streamlit run foodie_tour_app.py
💡 Notes
This app uses OpenWeatherMap for weather and Yelp Fusion API for restaurant discovery.
You can extend this project by adding support for more cities, Google Maps integration, or restaurant images.
