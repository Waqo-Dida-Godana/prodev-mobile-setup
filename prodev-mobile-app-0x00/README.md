# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Scaffolding Process

The project was scaffolded using the following steps:

1. Navigated to the parent project directory: `cd prodev-mobile-setup`
2. Initialized a new Expo project using the latest Expo Router template: `npx create-expo-app@latest .`
3. Modified the home screen in `app/(tabs)/index.tsx` by changing the default text "Welcome!" to "** First App Created**".

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Observations from reset-project command

Running `npm run reset-project` prompts the user to choose whether to move existing files to `/app-example` instead of deleting them. If 'Y' is selected, it creates the `app-example` directory and moves the `app`, `components`, `hooks`, `constants`, and `scripts` directories into it. Then, it creates a new blank `app` directory with `index.tsx` and `_layout.tsx` files. If 'N' is selected, it deletes the directories instead. The script encountered a permission error when attempting to rename directories, likely due to file locks from the development environment.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
