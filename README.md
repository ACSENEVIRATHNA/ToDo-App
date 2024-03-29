
# Flutter Task Manager App

Welcome to the Flutter Task Manager App repository! This Flutter project is designed to help users manage their tasks efficiently by adding tasks with associated dates and marking them as done upon completion. Users can also edit existing tasks or add new ones as needed.

## Features

- Add tasks with associated dates
- Mark tasks as done upon completion
- Edit existing tasks
- Offline functionality
- Data storage using Hive

## Screenshots

Here are some screenshots of the app:

1. ![Screenshot 1](screenshots/screenshot1.png)
2. ![Screenshot 2](screenshots/screenshot2.png)
3. ![Screenshot 3](screenshots/screenshot3.png)
4. ![Screenshot 4](screenshots/screenshot4.png)
5. ![Screenshot 5](screenshots/screenshot5.png)

## Prerequisites

Before running the app, ensure you have Flutter and its dependencies set up on your machine. You can follow the instructions on the [Flutter website](https://flutter.dev/docs/get-started/install) for installation.

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/ACSENEVIRATHNA/ToDo-App.git
```

2. Navigate to the project directory:

```bash
cd task_file_manager
```

3. Install dependencies using Flutter's package manager:

```bash
flutter pub get
```

4. Run the app:

```bash
flutter run
```

## Building the APK

To build the release APK, follow these steps:

1. Run the following command in the project directory to build the APK:

```bash
flutter build apk
```

2. Once the build process is complete, you can find the APK file in the following directory:

```
build\app\outputs\flutter-apk
```

3. Install the APK on your Android device:

   - Connect your Android device to your computer.
   - Navigate to the APK file location.
   - Install the APK on your device using `adb`:

   ```bash
   adb install app-release.apk
   ```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.
