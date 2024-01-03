# react-native-expo-devcontainer-template-for-post

This repository is a pre-configured example of a React Native Expo development environment using Dev Containers, constructed according to the procedures outlined in my post (https://zenn.dev/articles/a31b425bfb25db). It is provided for reference purposes related to my post and will not be updated. For the most up-to-date version of this template, please visit https://github.com/matsu3m/react-native-expo-devcontainer-template.

To set up the container, please follow the instructions below:

## Prerequisites

Ensure that you have the following installed on your machine:

- [VS Code](https://code.visualstudio.com/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) for VS Code
- [Expo Go](https://expo.dev/client) app on your smartphone

## Setup Instructions

1. Clone the Project and Open in VSCode:

    - Clone the project repository to your local machine.
    - Open the project in VS Code.

2. Reopen in Container:

    - Open the Command Palette in VS Code.
    - Select `Dev Containers: Reopen in Container`. VS Code will then start building the container and open the project inside it.

3. Start the Expo Server:

    - Once the container is running, open the terminal in VS Code.
    - Run the command `npm run start` to start the Expo server.
    - A QR code will appear in the terminal. Scan this with the Expo Go app on your smartphone to view the application.
