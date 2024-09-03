# React Native To-Do List App

This is a simple to-do list app built with React Native. The app allows users to add tasks, view them in a list, and mark them as complete by tapping on them.

## Features

- Add new tasks
- View all tasks for the day
- Mark tasks as complete by tapping on them (tasks are removed from the list)

## Getting Started

These instructions will help you set up the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [React Native CLI](https://reactnative.dev/docs/environment-setup) or [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Xcode for iOS development (for macOS users)
- Android Studio for Android development (for Windows/Linux users)

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/merttcetn/toDoApp
   ```
2. Navigate to the project directory:
   ```bash
   cd react-native-todo-app
   ```
3. Install the required dependencies:
   ```bash
   npm install
   ```

### Running the App

1. Start the Metro bundler:

   ```bash
   npx react-native start
   ```

2. Open a new terminal and run the app on iOS or Android:

   - For iOS (macOS only):

     ```bash
     npx react-native run-ios
     ```

   - For Android:
     ```bash
     npx react-native run-android
     ```

   If you're using Expo, run:

   ```bash
   expo start
   ```

## Project Structure

- `App.tsx`: Main component that manages state and renders the task input and list.
- `components/Task.tsx`: Component that renders an individual task item.

## Screenshots

![In App Screenshot](screenshots/screenshot.png)

## Built With

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
