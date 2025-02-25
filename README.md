![logo](https://github.com/user-attachments/assets/0d41b803-968a-41a8-809a-0dd3d91ec489)

## 1. Place the script within the <head> tag

```html
<head>
  <script src="/your_path/trackmyuser.js"></script>
</head>
```

## 2. Initialising the SDK

```js
window.TrackMyUser.init("YOUR_SDK_KEY")
```

## 3. Event Tracking

```js
var event = new window.TrackMyUserEvent("YOUR_EVENT_CODE");
event.setParam1('YOUR_EVENT_PARAMETER'); //optional
window.TrackMyUser.trackEvent(event)
```
