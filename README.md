# Android-ReactNative

An extremely simple demonstrarion of a react-native activity on an Android Application.

Created By Following the Docs:
  https://facebook.github.io/react-native/docs/integration-with-existing-apps.html

## Requirements
- Android Studio
- yarn

### To install yarn:
For Mac:
run `brew install yarn`

## Steps to run for the first time:
### In Project Directory:
1. run: `yarn add react-native`
  This will print warning similar to:
  
    `warning "react-native@0.52.2" has unmet peer dependency "react@16.2.0".`
  We just need to Install React

2. run: `yarn add react@"version_printed_in_console"`

3. run: `yarn start`(Start Development Build. See Package.json scripts/)

4. In Android Studio: Run the app.


To enable live reloading on emulator: command+M



