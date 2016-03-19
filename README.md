# feathers-react-native-chat
A React Native example chat app using Feathers that talks with the [feathers-chat](https://github.com/feathersjs/feathers-chat) server.

## Getting Started

1. Make sure you have [NodeJS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.

2. Clone down the repository

3. Install react native CLI

    ```
    npm install -g react-native-cli
    ```

4. Install your dependencies
    
    ```
    cd path/to/feathers-react-native-chat; npm install
    ```

5. Start the [feathers-chat](https://github.com/feathersjs/feathers-chat) server.

6. Start the iOS app

    ```
    react-native run-ios
    ```

7. Start the Android app

    ```
    react-native run-android
    ```

For IOS, alternatively run `npm start` on react native app (start React packager), then open+run the native app from Xcode (to launch on simulator or whichever device you like).

If you run into issues starting the apps please refer to the [React Native docs](https://facebook.github.io/react-native/docs/getting-started.html). It's most likely a problem with your environment.

## Database

You can clear the database on the server by running `rm data/*.db` from the root folder of `feathers-chat`. This will remove all messages and users and give you a fresh start.

## Changelog

__O.1.0__

- Initial release