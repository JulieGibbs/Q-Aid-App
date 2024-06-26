<p align="center">
  <img align="center" src="https://github.com/medtorch/Q-Aid/blob/master/misc/q_aid_logo_small1.png" alt="Q&Aid" width="50%">
</p>
<p align="center">
  <img align="center" src="https://pbs.twimg.com/profile_images/1114309924551417856/FKA4cm2x_400x400.png" alt="Q&Aid" width="30%">
  <img align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/800px-React-icon.svg.png" alt="Q&Aid" width="30%">
  <img align="center" src="https://pytorch.org/assets/images/pytorch-logo.png" alt="Q&Aid" width="20%">
</p>


![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Q&Aid](https://github.com/medtorch/Q-Aid/workflows/Q&Aid/badge.svg)

## Motivation

Read more about our motivation [here](https://github.com/JulieGibbs/Q-Aid-Motivation).

## Features

- :zap: Created using [React-Native](https://reactnative.dev/).
- :key: Authentication by [AWS Amplify](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/).
- :cyclone: Awesome chat created using [GiftedChat](https://github.com/FaridSafi/react-native-gifted-chat).
- :fire: Backed by the [PyTorch models](https://github.com/medtorch/Q-Aid-Models).

## Screens

#### Login

<p align="center">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/login_screen.jpg" alt="Q&Aid" width="20%">
</p>


#### Onboarding


<p align="center">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/onboard_screen1.jpg" alt="Q&Aid" width="20%">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/onboard_screen2.jpg" alt="Q&Aid" width="20%">
</p>

#### Chat


<p align="center">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/chat_screen1.jpg" alt="Q&Aid" width="20%">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/chat_screen2.jpg" alt="Q&Aid" width="20%">
  <img align="center" src="https://github.com/medtorch/Q-Aid-App/blob/master/misc/chat_Screen3.jpg" alt="Q&Aid" width="20%">
</p>


## Installation

Follow [these steps](https://reactnative.dev/docs/environment-setup) to setup your React Native environment.

Next, run the Metro server - you can use a script here
```
rm -rf node_modules
yarn install
rm -rf /tmp/metro-*

watchman watch-del-all
yarn start --reset-cache
```

Build and run the Android app
```
react-native run-android
```
Build and run the iOS app
```
react-native run-ios
```

## Next steps
 - :panda_face: React Native compatibility with PyTorch - https://github.com/medtorch/Q-Aid-App/issues/1
 - :two_hearts: iOS support.
## Contributors

See [CONTRIBUTORS.md](CONTRIBUTORS.md).

## License
[MIT License](https://choosealicense.com/licenses/mit/)



