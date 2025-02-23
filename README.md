# React Native Dimensions API: Incorrect Dimensions on Android Initial Render

This repository demonstrates a common issue with the `Dimensions` API in React Native on Android.  The problem occurs when attempting to access screen dimensions before the `Dimensions` object is fully initialized.  This typically happens during the initial render of a component.

The `IncorrectDimensions.js` file showcases the problematic code.  The `CorrectDimensions.js` file provides a solution using the `useEffect` hook to ensure the dimensions are available before use.

## Steps to Reproduce

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` or `yarn install` to install dependencies.
4. Run `react-native run-android` to launch the app on an Android emulator or device.
5. Observe the initial render and the console output for both files.