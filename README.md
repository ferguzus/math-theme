# MidtermApp

## Overview

MidtermApp is a mobile application developed using React Native and Expo. This guide will help you set up the project on your local machine.

## Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (Recommended version: 14.x or later)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

## Setup Instructions

Follow these steps to set up the project:

1. **Open your terminal.**
   
2. **Navigate to your desired directory (e.g., D: drive):**
    ```bash
   cd D:
    ```
3. **Install Expo CLI globally (if not already installed):**
    ```bash
    npm install -g expo-cli
    ```
4. **Initialize a new Expo project named "MidtermApp":**
    ```bash
    expo init MidtermApp
    ```
5. **Change to the project directory:**
    ```bash
    cd MidtermApp
    ```
6. **Install necessary packages for navigation and other features:**
    ```bash
    npx expo install @react-navigation/native @react-navigation/stack
    ```
    ```bash
    npx expo install react-native-screens react-native-safe-area-context
    ```    
    ```bash
    npx expo install react-native-vector-icons
    ```   
    ```bash
    npx expo install @expo-google-fonts/exo expo-font
    ```   

7. **Start the Expo development server:**
    ```bash
    npx expo start   
    ```
Cloning the Repository
If you need to clone the repository, use the following command:
    ```bash
    git https://github.com/ferguzus/math-theme
    ```

Running the App
After following the setup instructions, you can run the app on your device or emulator by scanning the QR code displayed in the terminal or in the Expo Go app.

## Additional Resources

- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [Expo Documentation](https://docs.expo.dev/)
