# Expo Linking API: Inconsistent Deep Link Handling on Android

This repository demonstrates an uncommon bug related to the Expo `Linking` API's inconsistent behavior on Android when handling deep links.  The issue centers around the unreliability of the `Linking.addEventListener` method, which may fail to trigger when a deep link is opened, particularly while the app is in the background. This leads to the application not responding to the expected deep link and impacting user experience. 

The `expoDeepLinkBug.js` file reproduces the problem. The `expoDeepLinkSolution.js` provides a potential solution. 