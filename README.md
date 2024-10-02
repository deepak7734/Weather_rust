 Weather Application

This is a simple command-line weather application written in Rust. The application allows you to check the current weather and get a 5-day weather forecast for any city or location using the OpenWeatherMap API. It utilizes asynchronous programming with the `tokio` runtime and the `reqwest` library for making HTTP requests, making it efficient and responsive.

Features:
1. Get Current Weather: Retrieve the current weather information for a specific city or location, including temperature, humidity, wind speed, and a brief weather description.
   
2. Get Forecast: Get a 5-day weather forecast for a given location with details such as temperature, humidity, wind speed, and weather conditions.

3.Easy Navigation: The application provides a simple menu-based interface to switch between different options and exit as needed.

How to Run:
To use the application, clone the repository and add your OpenWeatherMap API key in the code where it mentions `api_key`. After that, run the program using `cargo run` and follow the on-screen instructions.

Feel free to explore, modify, and contribute to this project!
