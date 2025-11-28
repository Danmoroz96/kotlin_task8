# kotlin_task8
Task 8: Weather app
Weather App (Task 8)

An Android application built with Jetpack Compose and Retrofit that fetches real-time weather data from the OpenWeatherMap API.

Features

API Integration: Uses Retrofit to make network requests to the OpenWeatherMap API.

JSON Parsing: Uses Gson to parse the JSON response into Kotlin data objects.

Asynchronous Data: Uses Kotlin Coroutines and ViewModel to fetch data without blocking the main UI thread.

Lazy List: Displays multiple weather results in a scrollable LazyColumn, allowing users to stack weather data for different cities.

Error Handling: Displays user-friendly error messages if the city is not found or the API key is invalid.

Technologies Used

Kotlin

Jetpack Compose (UI)

Retrofit 2 (Networking)

Gson (JSON Converter)

ViewModel & LiveData (Architecture)

Setup

Clone the repository.

Add your OpenWeatherMap API key in MainActivity.kt variable apiKey.

Sync Gradle and Run.


![Screenshot 2025-11-28 131122](https://github.com/user-attachments/assets/7c59eda1-a568-4374-9ba8-eb08f8032135)
![Screenshot 2025-11-28 131139](https://github.com/user-attachments/assets/e4b1cfd8-6393-44bd-bb3a-91c3fa2900d8)

