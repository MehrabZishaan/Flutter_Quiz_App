## Dependencies (pubspec.yaml)

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  google_fonts: ^3.0.1
  responsive_grid: ^2.1.0
  restart_app: ^1.1.0+1
  flutter_phoenix: ^1.1.0
  confetti: ^0.7.0


## Build Configuration
    Minimum Android version: 5.0 (API level 21)
    Minimum iOS version: 10.0

## Testing
    Unit testing will be implemented using the Flutter testing framework.

## Data Model (variables.dart)
    var urx = 'https://the-trivia-api.com/api/questions?categories=science&limit=1';
    var score = 0;
    var qCount = 0;

## Functional Requirements
    Load quiz questions from an external API.
    Display questions and multiple-choice options to the user.
    Allow the user to select an answer for each question.
    Calculate and display the total score at the end of the quiz.

## Non-Functional Requirements
    The app should be responsive and provide a good user experience across various devices.
    The app should load questions and display them within a reasonable time.
    The app should handle network errors gracefully.
```
