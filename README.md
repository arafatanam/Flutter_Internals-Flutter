# Flutter Internals

A collection of small demos and examples that explore Flutter's core behaviors — widget lifecycle, rebuilds, keys, UI updates, and platform-adaptive widgets. Designed and implemented while following the **Flutter & Dart** course by Maximilian Schwarzmüller.

## 📚 About the Course

This project was developed while taking the Flutter & Dart course by Maximilian Schwarzmüller:

**[Flutter & Dart - The Complete Guide [2025 Edition]](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/)**

The course provides hands-on exercises and real-world guidance for building professional Flutter apps.

## ✅ Features

- 🔧 Small, focused demos illustrating Flutter internals
- 🧩 Examples showing widget rebuilds, state changes, and lifecycle callbacks
- 🔑 Keys and state restoration examples (`keys/`)
- 🎛️ UI demos such as `demo_buttons.dart` and `ui_updates_demo.dart`
- 📱 Cross-platform support and platform-adaptive widgets
- 🧪 Lightweight tests and examples for learning best practices

## Installation

### Prerequisites

- Flutter SDK (version 3.9.0 or higher)
- An IDE (Android Studio, Visual Studio Code, or IntelliJ IDEA)
- A device/emulator for mobile testing or a browser for web

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/flutter_internals.git
   cd flutter_internals
   ```

2. **Get dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**

   ```bash
   flutter run
   ```

- Run in Chrome (web):

```bash
flutter run -d chrome
```

- Build release APK (Android):

```bash
flutter build apk --release
```

- Build iOS (macOS required for signing / build):

```bash
flutter build ios --release
```

## Project Structure

```
lib/
├── main.dart                 # App entry point and example routes
├── demo_buttons.dart         # Button demos and interactive examples
├── ui_updates_demo.dart      # Examples showing widget rebuilding & setState
└── keys/
    ├── checkable_todo_item.dart
    ├── keys.dart
    └── todo_item.dart
test/
├── widget_test.dart          # Example tests
```

## Key Files

### `main.dart`

- App entry point and simple navigation between demos

### `demo_buttons.dart`

- Interactive button examples (Material & Cupertino styles)

### `ui_updates_demo.dart`

- Demonstrates how UI updates are scheduled and how `setState` affects rebuilding

### `keys/` files

- Examples and explanations for using `Key`, `ValueKey`, and `GlobalKey` in practice

## Dependencies

This project uses the following packages (see `pubspec.yaml`):

- `cupertino_icons` — iOS-style icons
- Flutter's built-in material and cupertino widgets

## Development

### Build for production

```bash
flutter build apk --release
# or for iOS
flutter build ios --release
```

### Running tests

```bash
flutter test
```

## Key Learning Concepts

- Widget lifecycle and rebuild behavior
- When and how to use `Key`s for preserving state
- Efficient UI updates and avoiding unnecessary rebuilds
- Cross-platform widgets and adaptive UI patterns
- Simple test-driven examples for widget testing

---

**Explore Flutter internals with bite-sized demos!** 🔍

_Built with Flutter as part of an educational journey in mobile app development._
