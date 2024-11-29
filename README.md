Recipe Delight App
Assignment Name: Individual Assignment 2
Submission Date: 20/11/2024
GitHub Repository: Recipe Delight GitHub Link
Demo Video: (Provide video link here)

Introduction
The Recipe Delight App is a Flutter-based mobile application designed to allow users to explore and discover a variety of recipes. By integrating the Dummy JSON Recipe API, the app fetches and displays recipe data in an engaging, user-friendly interface. This project highlights the use of Flutter for app development, RESTful API integration, navigation, and state management.

Features
Home Screen
A welcoming page that introduces users to the app with a fun greeting message.
Provides navigation to the Recipes Screen via an interactive button.
Recipes Screen
Displays a list of recipes fetched from the Dummy JSON API.
Features recipe images, names, star ratings, and cooking times.
Includes error handling for failed API requests or empty data responses.
Recipe Details Screen
Displays detailed information about a selected recipe, including:
Recipe image and name.
Nutritional information such as calories and cooking time.
Full list of ingredients and cooking instructions (if available).

API Overview
API Used: Dummy JSON Recipe API
The API provides data such as recipe names, ingredients, cooking instructions, and nutritional details. Its comprehensive documentation and relevance to recipe applications made it an ideal choice for this project.

State Management
The app uses Provider for managing state, ensuring efficient widget-to-widget communication and seamless handling of API responses.

Development Process
Tools and Frameworks
IDE: Visual Studio Code
Framework: Flutter
Language: Dart
Steps Followed
Chose the Dummy JSON Recipe API from a list of free APIs.
Researched API usage through documentation and online tutorials.
Set up the Flutter project, including dependencies like http and provider.
Implemented API integration using HTTP requests.
Designed and built responsive UI components for all screens.
Tested the app for seamless functionality and robust error handling.

Challenges and Resolutions
API Limitations
Challenge: Difficulty understanding and utilizing the API initially.
Resolution: Extensive research, including finding a helpful YouTube tutorial that demonstrated a similar API usage. The tutorial provided insights on generating Dart classes for API integration, which were implemented in the recipes_model.dart.

Conclusion
The Recipe Delight App successfully demonstrates the integration of the Dummy JSON Recipe API with Flutter for building an interactive mobile application. It highlights effective navigation, state management, and error handling, providing a seamless user experience.

Setup Instructions
Prerequisites
Ensure you have Flutter SDK installed. You can download it from Flutter's official site.
Install a code editor like Visual Studio Code or Android Studio.
Ensure that you have a device emulator or a connected physical device for testing.
Steps to Set Up
Clone the repository:

git clone https://github.com/Skomaiya/food_recipe.git  


Navigate to the project directory:

cd food_recipe  


Install dependencies:

flutter pub get  


Run the app on a connected device or emulator:

flutter run  


Optional: Running on a Specific Platform
For Android:
Ensure an Android Virtual Device (AVD) is set up in Android Studio.
For iOS:
Ensure you have Xcode installed and set up on a macOS system.
