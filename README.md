# Flutter Playground

A Flutter demo application for experimenting with widgets, layouts, and mobile development patterns. Built as a learning sandbox for exploring Flutter's core concepts.

## Features

- Material Design UI components
- Image asset loading and display
- Android and iOS platform support
- Standard Flutter project structure with test scaffolding

## Tech Stack

- **Framework:** Flutter (Dart SDK >=2.16.2 <3.0.0)
- **Design:** Material Design (uses-material-design: true)
- **Icons:** Cupertino Icons
- **Platform:** Android (Kotlin) / iOS (Swift)

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (2.16.2+)
- Android Studio or Xcode for platform-specific builds

### Installation

```bash
# Clone the repository
git clone https://github.com/mhmalvi/flutter-playground.git
cd flutter-playground

# Install dependencies
flutter pub get

# Run the app
flutter run
```

### Running Tests

```bash
flutter test
```

## Project Structure

```
lib/
└── main.dart               # Application entry point
images/                     # Image assets
android/                    # Android platform configuration
ios/                        # iOS platform configuration
test/
└── widget_test.dart        # Widget tests
```

## License

MIT
