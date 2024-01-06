# dialog_page

## Introduction

`dialog_page` is a Dart package designed as a wrapper for Flutter's `showDialog` method. It simplifies the usage of dialogs in Navigator 2.0 by providing an easy-to-use interface for creating and managing dialog pages. This package aims to streamline the dialog creation process in Flutter applications, making it more accessible and efficient for developers.

## Features

- **Navigator 2.0 Support:** Specifically tailored for Navigator 2.0, ensuring compatibility and performance.
- **Easy Integration:** Seamlessly integrates with existing Flutter projects.
- **Customizable:** Offers various customization options like `barrierDismissible`, `barrierColor`, and more.

## Getting Started

### Installation

To use `dialog_page` in your Flutter project, either run

```bash
flutter pub add dialog_page
```

or add it manually to your `pubspec.yaml` file:

```yaml
dependencies:
  flutter:
    sdk: flutter
  dialog_page: ^1.0.0
```

### Basic Usage

Example usage of `DialogPage`:

```dart
import 'package:dialog_page/dialog_page.dart';

// Example widget showing how to use DialogPage
Widget build(BuildContext context) {
  return DialogPage(
    child: YourDialogWidget(),
    // Configure additional settings as needed
  );
}
```

## Documentation

For a complete list of properties and methods, please refer to the [API Documentation](https://github.com/HighLiuk/dialog_page/blob/main/lib/src/dialog_page.dart).

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, feel free to open an issue on our [GitHub repository](https://github.com/HighLiuk/dialog_page).
