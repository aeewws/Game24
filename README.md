# Game24

An Android Game 24 app built with Kotlin and Jetpack Compose.

## Build

Use the Gradle wrapper from the repository root:

```bash
./gradlew assembleDebug
```

## Test

Run the local unit tests with:

```bash
./gradlew testDebugUnitTest
```

## CI

GitHub Actions runs both `assembleDebug` and `testDebugUnitTest` on push and pull request.
