# app_badge_plus

A Flutter plugin for adding badges to your app icon.

![iOS](iOS.png)
![pixel](pixel.png)
![samsung](samsung.png)

## Supported Platforms``
- iOS
- Android
    - Samsung (pass)
    - Oppo (pass)
    - Vivo (pass)
    - Huawei (pass)
    - Xiaomi
    - LG
    - Sony
    - HTC
    - ZTX

## Mark

Starting with Android 8.0 (API level 26), notification badges—also known as notification 
dots—appear on a launcher icon when the associated app has an active notification. Users can 
touch & hold the app icon to reveal the notifications, along with any app shortcuts.

https://developer.android.com/develop/ui/views/notifications/badges

## Usage

To use this plugin, add `app_badge_plus` as a [dependency in your pubspec.yaml file](https://flutter.io/platform-plugins/).

```yaml
dependencies:
  app_badge_plus: ^1.0.0
```

## Example

```dart
import 'package:app_badge_plus/app_badge_plus.dart';

// Set badge
AppBadgePlus.updateBadge(5);

// Remove badge
AppBadgePlus.updateBadge(0);
```
