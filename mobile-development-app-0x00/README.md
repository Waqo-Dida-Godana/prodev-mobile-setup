# Create Your First Mobile App

## Objective

Set up your first mobile application using the Expo Router template. Document the scaffolding process and understand the file structure of a React Native application using Expo.

## Steps Followed for Scaffolding

1. Created the project directory `mobile-development-app-0x00`.
2. Created the subdirectory `app-example` inside it.
3. Navigated to the `app-example` directory.
4. Ran `npx create-expo-app@latest .` to scaffold the Expo project with the default Expo Router template in the current directory.
5. The scaffolding created the necessary files and directories for a React Native app using Expo, including `app/(tabs)/index.tsx`, `constants/Colors.tsx`, and other configuration files like `package.json`, `app.json`, etc.
6. Modified `app/(tabs)/index.tsx` to change the default text "Welcome!" to "** First App Created**".

## File Structure

The Expo Router template creates a file-based routing structure:

- `app/`: Contains the app's screens and layouts.
  - `(tabs)/`: A route group for tab-based navigation.
    - `index.tsx`: The home screen component.
- `constants/`: Holds constant values like colors.
  - `Colors.tsx`: Defines color schemes for light and dark themes.
- Other files: `package.json` for dependencies, `app.json` for Expo configuration, etc.

## Running and Testing the Application

- Ran `npx expo start` in the `app-example` directory.
- The command started the Expo development server.
- Displayed a QR code in the terminal.
- For iOS devices: Scan the QR code using the Camera app.
- For Android devices: Scan the QR code using the Expo Go app.
- The app loaded on the physical device, showing the modified home screen with "** First App Created**".

## Resetting the Application

- Ran `npm run reset-project` in the `app-example` directory.
- Observations: The command reset the project to its initial state. It removed any custom modifications, restored default files, and cleaned up the project as if it was just scaffolded. This is useful for starting fresh or undoing changes during development.

## Notes

- Ensure Node.js LTS and Expo Go are installed as per the previous setup.
- The app uses Expo Router for navigation, providing a simple way to handle routing in React Native apps.