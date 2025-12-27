# Package Structure

1. features/
Each feature has its own folder, making the app modular and scalable.
Subfolders for each feature:
data/: Handles data-related logic.
models/: Data models for the feature.
repositories/: Interfaces and implementations for data sources (e.g., APIs, databases).
domain/: Contains business logic.
entities/: Core entities used across the feature.
usecases/: Application-specific business logic.
presentation/: Handles UI and state management.
pages/: Screens or pages for the feature.
widgets/: Reusable widgets for the feature.
controllers/: State management (e.g., BLoC, Provider, Riverpod).
2. core/
Contains shared resources used across the app.
utils/: Utility functions (e.g., formatters, validators).
constants/: App-wide constants (e.g., API endpoints, keys).
themes/: Theme and styling configurations.
widgets/: Reusable widgets shared across features.
services/: Global services (e.g., network, authentication).
3. main.dart
The entry point of the application, initializing dependencies and routing.



## Root Directory
- `analysis_options.yaml`: Configuration for static analysis.
- `flutter_best_practices.md`: Documentation for Flutter best practices.
- `muslim_guide.iml`: IntelliJ project file.
- `pubspec.lock`: Lock file for Dart dependencies.
- `pubspec.yaml`: Dart dependencies and project metadata.
- `README.md`: Project overview and instructions.
- `ux_best_practices.md`: Documentation for UX best practices.

## Android Directory
- `build.gradle.kts`: Gradle build script for the Android project.
- `gradle.properties`: Gradle properties file.
- `gradlew`/`gradlew.bat`: Gradle wrapper scripts.
- `local.properties`: Local configuration for Android SDK.
- `settings.gradle.kts`: Gradle settings file.
- `app/`: Contains the main Android application code.
  - `build.gradle.kts`: Gradle build script for the app module.
  - `src/`: Source code and resources.
    - `debug/`: Debug-specific AndroidManifest.xml.
    - `main/`: Main source set.
      - `AndroidManifest.xml`: Main Android manifest file.
      - `java/`: Java source code.
      - `kotlin/`: Kotlin source code.
      - `res/`: Resources (e.g., drawable, layout).
    - `profile/`: Profile-specific AndroidManifest.xml.
  - `gradle/wrapper/`: Gradle wrapper configuration.

## iOS Directory
- `Flutter/`: Flutter-specific iOS configuration.
- `Runner/`: Main iOS application code.
  - `AppDelegate.swift`: App delegate implementation.
  - `Info.plist`: iOS app configuration.
  - `Assets.xcassets/`: Asset catalog.
    - `AppIcon.appiconset/`: App icons.
    - `LaunchImage.imageset/`: Launch images.
  - `Base.lproj/`: Storyboards.
    - `LaunchScreen.storyboard`: Launch screen storyboard.
    - `Main.storyboard`: Main storyboard.
  - `Runner.xcodeproj/`: Xcode project file.
  - `Runner.xcworkspace/`: Xcode workspace file.
  - `RunnerTests/`: Unit tests for the iOS app.

## lib Directory
- `main.dart`: Main entry point for the Flutter application.

## test Directory
- `widget_test.dart`: Widget tests for the Flutter application.

## web Directory
- `favicon.png`: Favicon for the web app.
- `index.html`: Main HTML file for the web app.
- `manifest.json`: Web app manifest.
- `icons/`: Icons for the web app.


