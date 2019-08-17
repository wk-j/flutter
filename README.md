## Flutter

- Download [SDK](https://flutter.dev/docs/get-started/install/macos)

## Android Studio + SDK

```bash
brew cask install android-studio
export ANDROID_HOME=/Users/wk/Library/Android/sdk
flutter doctor --android-licenses
```

## Path

```bash
/Users/wk/Library/Android/sdk/bin
```

## Create

```
flutter create --project-name hello -t app  --org wk  hello

cd hello

flutter emulators
flutter emulators --launch apple_ios_simulator
flutter run

fluter build apk
fluter build ios
```