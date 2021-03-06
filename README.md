# Neumorphism with Expo

web demo: [Expo Neumorphism](https://expo-neumorphism.calebnance.now.sh)

[![made with expo](https://img.shields.io/badge/MADE%20WITH%20EXPO-000.svg?style=for-the-badge&logo=expo&labelColor=4630eb&logoWidth=20)](https://github.com/expo/expo) [![supports iOS and Android](https://img.shields.io/badge/Platforms-Native-4630EB.svg?style=for-the-badge&logo=EXPO&labelColor=000&logoColor=fff)](https://github.com/expo/expo) [![supports web](https://img.shields.io/badge/Platforms-Web-4630EB.svg?style=for-the-badge&logo=EXPO&labelColor=000&logoColor=fff)](https://github.com/expo/expo)

[![follow @calebnance](https://img.shields.io/twitter/follow/calebnance.svg?style=for-the-badge&logo=TWITTER&logoColor=FFFFFF&labelColor=00aced&logoWidth=20&color=lightgray)](https://twitter.com/calebnance)

<p align="center">
  <img src="screenshots/screenshare-3.jpg?raw=true" />
</p>

### Inspiration / Tools

- [Alexander Plyuto's dribbble](https://dribbble.com/shots/7994421-Skeuomorph-Mobile-Banking)
- [Neumorphism in user interfaces](https://uxdesign.cc/neumorphism-in-user-interfaces-b47cef3bf3a6)
- [Neumorphism.io](https://neumorphism.io/#55b9f3)

## Table of Contents

- [Install & Build](#install--build)
- [Stats](#stats)
- [Linting](#linting)
- [Deploy to Zeit](#deploy-to-zeit)
- [Release Notes](#release-notes)

## Install & Build

Install: `yarn install`

Expo CLI: `npm install -g expo-cli` (if not already installed)

Run Project Locally: `expo start`

## Stats

- Expo SDK 36
- iOS, Android and PWA (Web App)
- React Navigation v5
- React Context
- PropTypes

## Linting

- run: `yarn lint` for a list of linting warnings/error in cli
- prettier and airbnb config
- make sure you have [prettier package](https://atom.io/packages/prettier-atom) installed on your atom/vscode editor
- then make sure to enable these options (packages → prettier):
  - eslint integration
  - stylelint integration
  - automatic format on save (toggle format on save)
- be aware of the `.prettierignore` file

## Deploy to Zeit

- to create a web build run: `yarn web-build` or `expo build:web`
- this will create a `/web-build` directory
- then cd into that directory and run: `now`
  - i named my deploy by running: `now --name expo-neumorphism`
  - which produced this url: https://expo-neumorphism.calebnance.now.sh

## Release Notes

### version 0.0.1 (current)

- started on [Expo SDK 36](https://blog.expo.io/expo-sdk-36-is-now-available-b91897b437fe)
- started with [React Navigation v5](https://reactnavigation.org/docs/en/getting-started.html)
- using [expo-linear-gradient](https://docs.expo.io/versions/latest/sdk/linear-gradient/)
