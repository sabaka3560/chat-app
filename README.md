# Flutter Chat App

## Overview

This Flutter-based group chat app offers a streamlined communication platform where users can sign in, join a single ongoing group chat, and experience seamless interaction with other participants. The app supports continuous conversations, ensuring that new users can access the complete chat history without losing context. It also includes essential features like user authentication, push notifications, and customizable profiles.

## Features

- **User Authentication**: Secure sign-in process for users to access the chat.
- **Continuous Group Chat**: One group chat with full message history accessible to all users, ensuring no one loses context.
- **Profile Customization**: Users can set their username and upload profile images for a personalized experience.
- **Push Notifications**: Real-time notifications keep users informed about new messages.
- **Cloud-Based Storage**: All messages are stored in the cloud, allowing users to access chats from any device without losing data.

## Installation

To run the app locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sabaka3560/chat-app.git
   cd group-chat-app
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase:**
   - Set up a Firebase project.
   - Add Firebase to your Flutter app by following the [official Firebase guide](https://firebase.flutter.dev/docs/overview/).
   - Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) and place them in their respective directories.

4. **Run the app:**
   ```bash
   flutter run
   ```

## Usage

1. **Sign In:** Users must sign in to access the chat.
2. **Join Chat:** Upon signing in, users are automatically added to the ongoing group chat, where they can view the entire chat history.
3. **Profile Setup:** Users can customize their profiles by setting a username and uploading a profile picture.
4. **Chat:** Start or continue conversations with all participants. All messages are instantly stored in the cloud.
5. **Receive Notifications:** Get notified of new messages with push notifications.

## Project Structure

- `lib/`: Contains the main Flutter app code.
  - `main.dart`: Entry point of the app.
  - `auth/`: Handles user authentication.
  - `chat/`: Manages chat functionalities and UI.
  - : Manages user profiles.
  - : Handles push notifications.

## Dependencies

- **Flutter SDK**
- **Firebase Authentication**: For secure user authentication.
- **Firebase Firestore**: For storing and retrieving chat messages.
- **Firebase Cloud Messaging**: For push notifications.
- **Provider**: For state management.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you have any suggestions or bug reports.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information. 
