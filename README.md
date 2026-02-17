Flutter Real-Time Chat App

A secure, real-time messaging application developed using Flutter and Firebase. It features a modern UI and robust security rules.

Features

- **Secure Authentication:** Email/Password login powered by Firebase Authentication.
- **Real-Time Chat:** Instant messaging using Cloud Firestore.
- **Data Security:** Custom Security Rules ensure only authenticated users can access messages.
- **Timestamps:** Messages display the sent time (HH:mm format).
- **Modern UI:** Clean design with colored bubbles distinguishing sender and receiver.
- **Identity Check:** Automatic alignment of messages (Right for "Me", Left for "Others").
Screenshots


Important Setup Note!

This project is open-source; however, for security and privacy reasons, the **Firebase API Keys** are **NOT** included in this repository.

To run this project on your local machine, you must connect it to **your own Firebase project**.

### How to Run

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/BatteriVoltas/Chat-App.git]
    ```

2.  **Create Your Own Firebase Project:**
    Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.

3.  **Enable Authentication & Firestore:**
    * **Authentication:** Sign-in method -> Email/Password (Enable).
    * **Firestore Database:** Create Database -> Start in production mode.

4.  **Connect Your Project (Terminal):**
    Run the following command in the project root (Requires FlutterFire CLI):
    ```bash
    flutterfire configure
    ```
    
5.  **Run the App:**
    ```bash
    flutter run
    ```

##  Project Structure

* `lib/auth_page.dart`: Handles Login and Registration logic.
* `lib/chat_page.dart`: Manages the Chat UI and Firestore connection.
* `lib/main.dart`: Entry point and session management.

