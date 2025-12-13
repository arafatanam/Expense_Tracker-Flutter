# Expense Tracker

A Flutter expense-tracking app showcasing responsive UI, Material 3 theming, and cross-platform support (Android, iOS, Web, macOS, Linux, Windows). Designed as part of a Flutter learning journey.

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

- Flutter SDK (version 3.9.0 or higher) and Dart
- An IDE (Android Studio, Visual Studio Code, or IntelliJ IDEA)
- A device or emulator for mobile testing or a browser for web

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
├── main.dart                      # App entry point, themes and Material 3 seed color
├── models/
│   └── expense.dart               # Expense model, category enum, bucket grouping
└── widgets/
   ├── expenses.dart              # Main expenses screen and stateful logic
   ├── new_expense.dart           # Modal sheet for creating new expenses
   ├── chart/                      # Chart widgets for category-based visualization
   └── expenses_list/              # Expense list and item UI
```

## Key Files

### main.dart

- App entry point and Material 3 theme definitions (light & dark seed colors)

### models/expense.dart

- Expense data model with UUID; category enum; `ExpenseBucket` for charting

### widgets/expenses.dart

- Stateful screen that manages expenses list, modal sheet for adding items, remove and undo operations, and responsive layout

### widgets/new_expense.dart

- Input form for adding new expenses with validation and platform-adaptive dialogs

### widgets/chart/

- Chart widgets and `ChartBar` for category-based visualizations

### widgets/expenses_list/

- Expense list and `ExpenseItem` with swipe-to-delete and animated transitions

## Dependencies

This project uses the following packages:

- `intl` — Date formatting and localization
- `uuid` — ID generation for `Expense` instances
- Flutter's built-in material, cupertino widgets, and core packages

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
