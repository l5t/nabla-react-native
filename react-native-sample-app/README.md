# Nabla React Native SDK demo app

This app contains a basic setup of the React Native Nabla SDK so that you can quickly test the features using our setup guide in the console.

## Prerequisites

This guide assumes that you already have access to the Nabla console. If you don't, you need to register an organization at https://nabla.com/

You'll also need to have the React Native environment setup to build the app.

## Setup

1. Clone the repository
2. Head to [https://`your_organisation_id`.pro.nabla.com/developers/sdk-setup-guide]()
3. Follow the setup guide to create a test patient and get your public API key and temporary `access_token` and `refresh_token` to use for the demo

> At this stage, you should have a public API key and 2 tokens

4. Open the `src/App.tsx` file and replace the value of `apiKey` with the public API key, and the `accessToken` and `refreshToken` values with the 2 tokens.
5. ```sh
   yarn install
   cd ios && pod install && cd ..
   yarn ios
   yarn android
   ```

You should now be able to use the demo app to create a new conversation and send messages.

## Next step: integrate the SDK in your app

To integrate the SDK into your app, follow our [README](https://github.com/nabla/nabla-react-native) and get all the details in our [developer documentation](https://docs.nabla.com).

## Need more help?

If you need any help with the set-up of the SDK or the Nabla platform, please contact us on [our website](https://nabla.com). We are available to answer any question.
