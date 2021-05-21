# react-native-unimodules-example

This is a test project for a React Native app that

- Runs on tvOS
- Includes patches needed to make `react-native-unimodules` work (or at least compile)

See [this doc](https://docs.expo.io/bare/installing-unimodules/) for details on using `react-native-unimodules`.

The `patches` directory has all the patches needed.  Mostly, changes were needed to the Expo and Unimodule podspecs to allow the tvOS platform.  A few actual code changes were needed in certain places.

The project was generated from `react-native init TestApp --template=react-native-tvos` so that the tvOS targets would be present in the Xcode project.
 
