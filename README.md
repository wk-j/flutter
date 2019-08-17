## Flutter [![CircleCI](https://circleci.com/gh/wk-j/flutter.svg?style=svg)](https://circleci.com/gh/wk-j/flutter)


Download [SDK](https://flutter.dev/docs/get-started/install/macos)

## Android Studio + SDK

```bash
brew cask install android-studio
export ANDROID_HOME=/Users/wk/Library/Android/sdk
flutter doctor --android-licenses
```

## Create

```bash
flutter create --project-name hello -t app  --org wk  hello

cd hello

flutter emulators
flutter emulators --launch apple_ios_simulator
flutter test
flutter run

fluter build apk
fluter build ios
```