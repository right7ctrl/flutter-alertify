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
| alertType | Pick your alert type such as success, error, warning, info and none |
| content | some content to show user |
| title | | The title that shown to user |
| buttonText | | The button text |
| animationType | | AnimationType.leftToRight, AnimationType.rightToLeft, AnimationType.topToBottom, AnimationType.bottomToTop, AnimationType.inToOut, AnimationType.outToIn |