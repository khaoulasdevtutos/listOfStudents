# Student Management App

This is a Student Management application built with React Native and SQLite. The app allows users to add, edit, and delete student records. 

# Author : Khaoula's DEV tutos
# Date : 8 juillet 2024

# Description :

## Features

- Add new students
- Edit existing students
- Delete individual students
- Delete all students
- Display a list of students with their details

## Technologies Used

- React Native
- Expo
- SQLite (via `expo-sqlite`)

## useSQLiteContext and SQLiteProvider
These hooks and components are used to manage the SQLite database connection.

- SQLiteProvider: This component wraps the main application and provides the SQLite database context. It ensures the database is initialized when the app starts.
- useSQLiteContext: This hook provides access to the SQLite database instance within components.

## Setup and Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/khaoulasdevtutos/listOfStudents.git  
    cd listOfStudents
    ```

2. **Install dependencies:**

    Make sure you have `npx` installed. Then, install the project dependencies:

    ```sh
    npx expo install
    ```

3. **Run the app:**

    Start the Expo development server:

    ```sh
    npx expo start
    ```

    You can then open the app in an emulator or on a physical device using the Expo Go app.



