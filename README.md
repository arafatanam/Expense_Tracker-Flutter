# Expense Tracker

A beautifully designed and feature-rich Flutter expense tracking application that helps you manage your finances with ease. This project was created as part of a Flutter learning journey to master cross-platform mobile app development.

## 📚 About the Course

This project was developed while taking the Flutter & Dart course by Maximilian Schwarzmüller:

**[Flutter & Dart - The Complete Guide [2025 Edition]](https://www.udemy.com/course/learn-flutter-dart-to-build-ios-android-apps/)**

The course provides comprehensive training in Flutter and Dart for building professional iOS and Android applications.

## Features

- 💰 Track and manage your expenses effectively
- 📊 Visual expense charts and analytics
- 🎨 Modern and intuitive UI design
- ➕ Easy expense entry with categorization
- 📱 Responsive design for all screen sizes
- 🗑️ Delete and manage expense history
- 📈 Real-time balance calculations
- ⚡ Smooth transitions and animations

## Installation

### Prerequisites

- Flutter SDK (version 3.0.0 or higher)
- Dart SDK (version 3.0.0 or higher)
- An IDE (Android Studio, VS Code, or IntelliJ IDEA)
- An emulator or physical device for testing

### Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/arafatanam/Expense_Tracker-Flutter.git
   cd Expense_Tracker-Flutter
   ```

2. **Get dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── main.dart                      # Application entry point
├── models/
│   └── expense.dart               # Expense model class
└── widgets/
    ├── expenses.dart              # Main expenses view and state management
    ├── new_expense.dart           # Add new expense form
    ├── chart/                      # Chart widgets for analytics
    └── expenses_list/              # Expense list display components
```

## Key Files

### main.dart

- Application entry point
- Sets up MaterialApp and initial theme configuration

### models/expense.dart

- Defines the Expense data model
- Contains expense properties and methods

### widgets/expenses.dart

- Main widget managing overall expense state
- Handles expense addition, deletion, and filtering logic

### widgets/new_expense.dart

- Form for adding new expenses
- Handles expense input validation and submission

### widgets/chart/

- Chart components for visualizing expense data
- Displays expense analytics and summaries

### widgets/expenses_list/

- List components for displaying tracked expenses
- Individual expense item rendering

## Dependencies

This project uses the following Flutter packages:

- `flutter/material.dart` - For Material Design components
- `intl` - For date and time formatting

## Development

### Building for production

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

This project demonstrates important Flutter development concepts:

- State management and StatefulWidget usage
- Custom widget composition and reusability
- Form handling and input validation
- Data modeling and organization
- List rendering and dynamic UI updates
- Date and time handling
- Chart and visualization implementation
- Error handling and user feedback

---

**Manage your finances smartly!** 💸

_Built with Flutter as part of an educational journey in mobile app development._
