# cordova-plugin-ios-decimal-keyboard

A simple plugin to allow the decimal point to be accessible via the keyboard in iOS / iPhone.

### Installing

```
cordova plugin add https://github.com/mrchandoo/cordova-plugin-decimal-keyboard.git
```
## Usage

```
<input type="text" pattern="[0-9]*" decimal="true">
```

### Multiple decimals

```
<input type="text" pattern="[0-9]*" decimal="true" allow-multiple-decimals="true">
```

## Known Issues
* Screen rotation unsupported.
