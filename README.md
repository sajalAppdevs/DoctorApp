# Doctor Appointment App

A modern medical doctor appointment application developed using Flutter, designed to streamline the process of booking and managing medical appointments. The app features a clean Material Design UI/UX and integrates Firebase for real-time notifications.

## Features

### Core Functionality
- **Appointment Scheduling**: Easy-to-use interface for booking appointments with doctors
- **Doctor Profiles**: Detailed profiles of medical professionals
- **Chat System**: Real-time messaging between patients and doctors
- **Symptom Tracking**: Built-in system for tracking common symptoms like:
  - Temperature
  - Snuffle
  - Fever
  - Cough
  - Cold

### Technical Features
- **Firebase Integration**
  - Push notifications for appointment reminders and updates
  - Background message handling
  - Real-time chat functionality
- **Local Notifications**: Enhanced user engagement with local notification support
- **Biometric Authentication**: Secure access using device biometric capabilities
- **Material Design**: Modern and responsive UI following Material Design guidelines

## Screenshots

![App Screenshots](./assets/doctor_app.png)

## Technical Requirements

### Prerequisites
- Flutter SDK
- Firebase account and configuration
- Android Studio/VS Code with Flutter plugins

### Dependencies
- `firebase_core`: Firebase core functionality
- `firebase_messaging`: Push notification handling
- `flutter_local_notifications`: Local notification management
- `flutter/material.dart`: Material Design widgets

## Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
cd DoctorApp
```

2. **Install dependencies**
```bash
flutter pub get
```

3. **Configure Firebase**
- Set up a Firebase project
- Add your `google-services.json` to the Android app
- Configure Firebase messaging in the app

4. **Run the app**
```bash
flutter run
```

## Project Structure

- `lib/screens/`: Contains all the main screen implementations
  - `Home_Screen.dart`: Main dashboard
  - `appointment_screen.dart`: Appointment management
  - `messages_screen.dart`: Chat functionality
- `android/`: Android-specific configurations
- `assets/`: Image and other media resources

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
