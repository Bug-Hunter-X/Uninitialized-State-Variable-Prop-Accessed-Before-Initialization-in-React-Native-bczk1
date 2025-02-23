# Uninitialized State Variable/Prop Accessed Before Initialization in React Native
This repository demonstrates an example of the error that occurs when accessing a state variable or prop before it has been initialized in React Native.  The bug.js file shows the problematic code and bugSolution.js provides the corrected version.  The issue often manifests when attempting to use state or props within the render method before React has had a chance to properly set their values. This commonly occurs during the component's initial rendering phase or after an asynchronous operation that updates the state.

## How to Reproduce
1. Clone the repository.
2. Navigate to the project directory.
3. Run `npx react-native run-android` (or `npx react-native run-ios`).
4. Observe the error message in the console or the app's behavior.