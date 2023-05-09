# cordova-plugin-app-splashscreen
This plugin adds an opening animation on top of the Cordova plugin splash screen plugin.

The animation set in the plugin is fixed and can be modified by oneself.

## Installation
    cordova plugin add cordova-plugin-app-splashscreen
## Preferences
Same as Cordova plugin splash screen，Reference link is `https://github.com/apache/cordova-plugin-splashscreen`

#### config.xml
- `IsOpenAnimation` (boolean, default to `true` ). Set to false to disable the animation, To enabled the animation add the following preference to `config.xml`:
```xml
    <preference name="IsOpenAnimation" value="true" />
```
