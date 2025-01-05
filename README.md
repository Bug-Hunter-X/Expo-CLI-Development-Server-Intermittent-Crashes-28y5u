# Expo CLI Development Server Intermittent Crashes

This repository demonstrates a bug encountered with the Expo CLI, where the development server would intermittently crash without providing meaningful error messages. The app would build and function correctly on a simulator, however, upon making code changes the server would become unresponsive.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install` or `yarn install`.
4. Run `expo start`.
5. Make small changes to the app code in `App.js`.
6. Observe the Expo development server. The server may crash without any clear indication in the terminal.  This behaviour is inconsistent.

## Solution

The solution involves investigating system resource constraints (memory and CPU) and exploring potential conflicts with other software or processes.  It's also recommended to upgrade Expo CLI and related packages to the latest versions to benefit from bug fixes and improvements. A detailed solution is provided in `expoBugSolution.js` along with explanations.

## Additional Information

Please refer to the `expoBug.js` file for the problematic code and `expoBugSolution.js` for the corrected code and solution.