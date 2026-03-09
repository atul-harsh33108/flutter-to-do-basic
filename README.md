# Flutter To-Do Basic ->

A simple cross‑platform To‑Do mobile application built with Flutter that
helps users manage daily tasks efficiently.

The application supports creating tasks, marking them as completed,
deleting tasks, and storing tasks locally using SharedPreferences so
that tasks persist even after restarting the application.

This project demonstrates Flutter UI development, basic state
management, and local data persistence.

------------------------------------------------------------------------

## Features

-   Add new tasks
-   Mark tasks as completed or incomplete
-   Delete tasks
-   Persistent local storage using SharedPreferences
-   Automatic task restoration when the app restarts
-   Simple and responsive Material UI

------------------------------------------------------------------------

## Tech Stack

-   Flutter -- Cross‑platform mobile app framework
-   Dart -- Programming language used for Flutter development
-   SharedPreferences -- Local persistent storage
-   Material UI -- UI components and design system
-   Git & GitHub -- Version control and project hosting

------------------------------------------------------------------------

## Project Structure

    flutter-to-do-basic/
    │
    ├── lib/
    │   └── main.dart
    │
    ├── android/
    ├── ios/
    ├── test/
    │
    ├── pubspec.yaml
    └── README.md

------------------------------------------------------------------------

## How the Application Works

1.  The user enters a task in the input field.
2.  The task is added dynamically to the task list.
3.  Users can mark tasks as completed or delete them.
4.  Tasks are saved locally using SharedPreferences.
5.  When the application restarts, saved tasks are automatically loaded.

------------------------------------------------------------------------

## Installation & Setup

### Clone the repository

    git clone https://github.com/atul-harsh33108/flutter-to-do-basic.git

### Navigate to the project folder

    cd flutter-to-do-basic

### Install dependencies

    flutter pub get

### Run the application

    flutter run

You can run the application on: - Android Emulator - iOS Simulator -
Physical Android or iOS device

------------------------------------------------------------------------

## Screenshots

(Add screenshots here after capturing them from the app)

Example:

    ![Home Screen](assets/screenshots/home.png)
    ![Task Added](assets/screenshots/add_task.png)

------------------------------------------------------------------------

## Learning Outcomes

-   Flutter widget-based UI development
-   State management using StatefulWidgets
-   Local data persistence using SharedPreferences
-   Dynamic list updates and UI rebuilds
-   Basic Flutter project structure and development workflow

------------------------------------------------------------------------

## Future Improvements

-   Task editing feature
-   Task filtering (All / Completed / Pending)
-   Dark mode support
-   State management using Provider or BLoC
-   Cloud sync using Firebase
-   Task reminders and notifications

------------------------------------------------------------------------

## Author

Atul Harsh


GitHub: https://github.com/atul-harsh33108\


------------------------------------------------------------------------

## License

This project is open source and available under the MIT License.
