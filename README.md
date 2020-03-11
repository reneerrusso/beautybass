# BeautyPass React Native Application
Info about BeautyPass

## Getting started

1. Install React Native as described at [https://facebook.github.io/react-native/docs/getting-started.html#content](https://facebook.github.io/react-native/docs/getting-started.html#content)
2. Clone this repository
3. Run `npm install` , all required components will be installed automatically

    ### iOS
      
    1. Run `pod install` from `react-native-demo/ios` folder
    2. Run `npx react-native run-ios` to start the simulator [Specifying a device](http://reactnative.dev/docs/running-on-simulator-ios)
    
    Note: To enable ios push notifications in demo project, follow the [the instructions](http://voximplant.com/blog/push-notifications-for-ios/) to add certificates to the Voximplant Cloud
    
    ### Android
    
    no steps required
        
    Note: 
    To enable andorid push notifications in demo preoject:
    
    1. Follow [the instructions](http://voximplant.com/blog/push-notifications-for-android/) to add the certificates to the Voximplant Cloud 
    2. Add `google-services.json` file to android/app folder
    3. Open `app/build.gradle` file and uncomment the `//apply plugin: 'com.google.gms.google-services'` line

4. It is recommended to run `react-native start` command from root project directory.
5. Run your project from XCode (`Cmd+R`) for iOS, or use `react-native run-android` to run your project on Android.

## Useful links
Official guides:
- [React Native documentation](http://reactnative.dev/)