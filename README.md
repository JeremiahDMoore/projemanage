# ProjeManage

ProjeManage is a Kanban-style project management tool inspired by Trello. It allows users to create, read, update, and delete movable cards on a Kanban board, facilitating efficient project tracking and task management.

## Features

- **User Authentication**: Secure sign-up and login functionality using Firebase Authentication.
- **Real-time Database**: Utilizes Firestore for real-time data storage and retrieval.
- **Kanban Board**: Interactive board with draggable cards representing tasks.
- **CRUD Operations**: Create, read, update, and delete tasks seamlessly.
- **Responsive Design**: Optimized for various screen sizes, ensuring usability across devices.

## Technologies Used

- **Kotlin**: Programming language for Android development.
- **Android Studio**: Integrated Development Environment (IDE) for Android app development.
- **Firebase Authentication**: For managing user authentication.
- **Firestore**: NoSQL database for storing project and task data.
- **Gradle**: Build automation tool used in the Android ecosystem.

## Installation

To set up and run ProjeManage locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/JeremiahDMoore/projemanage.git
   cd projemanage
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Select "Open an existing project" and navigate to the cloned repository directory.
   - Allow Android Studio to set up the project and download any necessary dependencies.

3. **Configure Firebase**:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add an Android app to your Firebase project with the package name matching that of ProjeManage.
   - Download the `google-services.json` file provided by Firebase.
   - Place the `google-services.json` file in the `app` directory of your Android Studio project.
   - Ensure Firebase Authentication and Firestore are enabled in your Firebase project settings.

4. **Build and Run the Application**:
   - Connect an Android device or start an emulator.
   - Click the "Run" button in Android Studio to build and deploy the app.

## Usage

- **Sign Up/In**: Create a new account or log in with existing credentials.
- **Create Board**: Start a new project by creating a board.
- **Add Tasks**: Within a board, add tasks as cards.
- **Move Tasks**: Drag and drop tasks between columns to reflect their status.
- **Edit/Delete Tasks**: Long-press on a task to edit or delete it.


## Acknowledgments

ProjeManage is developed to provide an open-source alternative for project management, inspired by tools like Trello, and built to demonstrate the capabilities of Kotlin and Firebase in creating dynamic Android applications.
