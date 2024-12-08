# AirBnB Clone

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.


For starter Project checkout the branch
```starter-files```

### Ensure Prerequisites Are Installed
Before setting up the project, make sure you have the following installed on your machine:

Flutter SDK: Install Flutter if you haven't already.
Dart SDK: Typically comes bundled with Flutter.
IDE: Preferably Android Studio, Visual Studio Code, or IntelliJ IDEA.
Git: Since you've cloned the repository, Git is already installed.
### Verify Flutter Installation
Open your terminal or command prompt and run:

```flutter doctor```
This command checks your Flutter installation and displays a report of the status of your Flutter setup. Ensure that all required components are installed and there are no critical issues. Address any issues highlighted by flutter doctor before proceeding.

### Navigate to the Project Directory
Change your current directory to the cloned project:

```cd path/to/your/cloned/flutter_project```
Replace path/to/your/cloned/flutter_project with the actual path where you cloned the repository.

### Install Project Dependencies
Fetch all the dependencies listed in the pubspec.yaml file by running:

```flutter pub get```
This command downloads all the necessary packages required for the project.

### Handle Platform-Specific Dependencies
Depending on the project, you might need to install additional dependencies:

iOS Projects: Navigate to the ios directory and install CocoaPods dependencies:

```cd ios```

```pod install```

```cd ..```

Ensure you have CocoaPods installed on your machine.

Android Projects: Typically, Flutter handles Android dependencies automatically. However, ensure you have the latest Android SDK and necessary tools installed via Android Studio.

### Run the Application
Ensure you have a simulator/emulator running or a physical device connected.

Run on an Emulator or Simulator:

Android: Start an Android emulator via Android Studio or the command line.
iOS: Start an iOS simulator via Xcode.
Run the App:

```flutter run```

This command builds and runs the app on the connected device or emulator.