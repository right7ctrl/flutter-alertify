# Alertify

Beautiful flutter alerts!



## Using

 Alertify(
  content: 'Some content here',
  context: context,
  isDismissible: true,
  title: 'Alertify',
  alertType: AlertifyType.success,
  buttonText: 'OK',
  animationType: AnimationType.outToIn
).show();



## Properties

| Property | Action |
---------------------
| alertType | Pick your alert type such as success, error, warning, info and none |
--------------------
| content | some content to show user |
| title | | The title that shown to user |
| buttonText | | The button text |
| animationType | | AnimationType.leftToRight, AnimationType.rightToLeft, AnimationType.topToBottom, AnimationType.bottomToTop, AnimationType.inToOut, AnimationType.outToIn |


# ✨ Flutter Alertify

[![pub package]](https://pub.dartlang.org/packages/alertify)

A collection of beautiful animated dialogs.

## 🎖 Installing

```yaml
dependencies:
  alertify: "^0.0.1"
```

### ⚡️ Import

```dart
import 'package:alertify/alertify.dart';
```

## 🎮 How To Use

```dart
 Alertify(
  content: 'Some content here',
  context: context,
  isDismissible: true,
  title: 'Alertify',
  alertType: AlertifyType.success,
  buttonText: 'OK',
  animationType: AnimationType.outToIn
).show();
```

### ❗️ Note

-

## ⭐️ License

MIT License
