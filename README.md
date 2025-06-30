🌤️ Indian Weather App
A beautifully designed, modern weather web application tailored specifically for Indian cities. Instantly fetch and display the current weather conditions of major cities across India using mock data or OpenWeatherMap API.


📌 Features
🎯 Search for real-time weather by Indian city names (e.g., Delhi, Mumbai, Hyderabad).

🌈 Clean, modern UI with subtle animations and cloud effects.

☁️ Weather info includes temperature, humidity, pressure, wind speed, and "feels like" data.

🌤️ Weather icon changes dynamically based on the forecast.

⚡ Mock weather data for 20+ major Indian cities (great for demos without API dependency).

📱 Fully responsive design (mobile and desktop friendly).

🚀 Technologies Used
HTML5

CSS3 (including Flexbox, Grid, Animations)

JavaScript (ES6)

OpenWeatherMap API (optional for real-time data)

🛠️ How to Use
🔧 Option 1: Use with Mock Data (No API Key Needed)
Best for demonstration or offline environments

Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/indian-weather-app.git
cd indian-weather-app
Open index.html in your browser.

bash
Copy
Edit
start index.html
Done! Try searching for cities like Mumbai, Delhi, Hyderabad, etc.

🌐 Option 2: Use Live Data with OpenWeatherMap API
For real-time weather data (requires free API key)

Sign up at OpenWeatherMap and get your API key.

Replace this line in script:

js
Copy
Edit
const API_KEY = 'your_openweathermap_api_key_here';
Replace the mock data section or modify the getWeather() function to fetch from the API instead of mock data.

Done! Now your app pulls real weather data from OpenWeatherMap.

🧠 Learning Highlights
DOM manipulation and event handling

Working with API responses and mock data

Dynamic UI updates

Creative UI/UX design principles

Responsive and accessible frontend development


📍 Indian Cities Supported in Demo
Mumbai, Delhi, Hyderabad, Bangalore, Chennai, Kolkata, Pune, Ahmedabad, Jaipur, Lucknow, Kochi, Goa, Shimla, Srinagar, Bhubaneswar, Thiruvananthapuram, Chandigarh, Indore, Nagpur, Coimbatore

💡 Future Enhancements
Integrate full OpenWeatherMap API functionality

Add location-based weather (Geolocation API)

5-day forecast charts

Voice input for city search

Save favorite cities

🧑‍💻 Author
BOYINA Sankar
🔗 GitHub | 🔗 LinkedIn
Passionate frontend developer exploring full-stack web apps.

📄 License
This project is open-source and available under the MIT License.
