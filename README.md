# Dynamsoft Capture Vision Flutter Samples

This repository contains multiple samples that show you how use the Dynamsoft Capture Vision Flutter SDK.

## Requirements

### Dev tools

* Latest [Flutter SDK](https://flutter.dev/)
* For Android apps: Android SDK (API Level 21+), platforms and developer tools
* For iOS apps: iOS 13+, macOS with latest Xcode and command line tools

### Mobile platforms

* Android 5.0 (API Level 21) and higher
* iOS 13 and higher

## Official Docs

- [Dynamsoft Capture Vision Flutter](https://www.dynamsoft.com/capture-vision/docs/mobile/programming/flutter/)

## Samples

| Sample Name                  | Description                                                                                                                              |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| [ScanDocument](ScanDocument) | This sample illustrates how to detect and deskew document pages from the video stream.                                                   |

## How to build and run a sample

### Step 1: Enter a sample folder that you want to try

```bash
cd ScanDocument
```

### Step 2: Fetch and install the dependencies of this example project via Flutter CLI:

```
flutter pub get
```

Connect a mobile device via USB and run the app.

### Step 3: Start your application

**Android:**

```
flutter run -d <DEVICE_ID>
```

You can get the IDs of all connected devices with `flutter devices`.

**iOS:**

Install Pods dependencies:

```
cd ios/
pod install --repo-update
```

Open the **workspace**(!) `ios/Runner.xcworkspace` in Xcode and adjust the *Signing / Developer Account* settings. Then, build and run the app in Xcode.

> [!NOTE]
>- The license string here grants a time-limited free trial which requires network connection to work.
>- You can request a 30-day trial license via the [Request a Trial License](https://www.dynamsoft.com/customer/license/trialLicense?product=dcv&utm_source=guide&package=mobile) link.

## Support

https://www.dynamsoft.com/company/contact/
