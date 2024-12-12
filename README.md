# Fitness Apllication

This is a fitness management app that allows users to interact with a list of fitness-related services or locations. The app offers several features to manage, view, and customize fitness data, providing a user-friendly interface for accessing fitness information.

## Features
- View Fitness List: Display a list of fitness-related services or locations.
- Add Fitness Entries: Allows users to add new fitness entries (name and address).
- Language Settings: Users can change the app's language through the settings.
- About Section: Provides information about the app and its creators.
- Logging: Logs fitness data for debugging purposes.
- Exit App: Provides an option to close the app.

## Installation

Clone this repository:

`git clone https://github.com/zbrdarovski/fitness.git`

Open the project in Android Studio.
Build and run the app on a physical device or emulator.

## Dependencies

- Timber for logging
- AndroidX libraries for modern Android development

## Quality Assurance

The applicaton was thoroughly tested on Samsung Galaxy A40.

## Project Structure

`./app/src/main/res`:
- drawable-v24: Contains resources for devices running Android API level 24 (Nougat) and above.
- drawable: General folder for image resources, typically used for all devices.
- font: Stores font files to be used in the app.
- layout: Contains XML files that define UI layouts.
- mipmap-anydpi-v26, mipmap-hdpi, mipmap-mdpi, mipmap-xhdpi, mipmap-xxhdpi, mipmap-xxxhdpi: Various folders for storing app launcher icons with different resolutions for various device screen densities.
- values: A standard folder for storing XML files that define values like colors, dimensions, strings, and styles.

`./app/src/main/java/fitness` contains application activities

`./app/src/main/AndroidManifest.xml` is a crucial component of any Android application. It provides essential information about the app to the Android system, including app permissions, components (such as activities, services, and broadcast receivers), themes, and other configurations.

## License
This project is not licensed for public use. The code is protected by copyright law.  
Viewing is permitted for evaluation purposes only. Copying, modifying, or distributing the code is strictly prohibited.
