Medicare Pharmacy App

This is an Android application designed to support pharmacy management by providing features for stock administration and inventory tracking. The app allows pharmacy admins to add new stock items and check existing inventory through a user-friendly interface.

Features

Add New Stock:
Admins can input product details such as name, quantity, and price, and save them into the system.

Check Stock:
View and verify existing stock information including product name, price, and quantity.

Automated Testing:
The project includes Espresso-based UI test cases for ensuring correctness of input fields and interactions:

AdminStockTest – validates adding new stock items.

CheckStockTest – validates displaying correct stock details.

ExampleInstrumentedTest – verifies app context and package consistency.

Tech Stack

Language: Java

Framework: Android SDK

Testing: Espresso, JUnit

Build System: Gradle

Project Structure

app/ – Main Android application source code

gradle/ – Build configuration files

tests/ – Contains instrumented tests for stock management features

How to Run

Clone this repository

Open the project in Android Studio

Sync Gradle dependencies

Run the app on an emulator or a physical device

License

This project is for educational purposes.
