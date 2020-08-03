# GoMarketplace

<p align="center">
    <img src="https://github.com/felipedmsantos95/gomarketplace/blob/master/img/GoMarketplace.jpg"/>
    </br>
    <a href="readme_en.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="readme.md">Português</a>&nbsp;&nbsp;&nbsp;
</p>

## App Preview

<p align="center">
  <img src="https://github.com/felipedmsantos95/gomarketplace/blob/master/img/gomarketplace.gif"/>
</p>

## About

React-Native mobile application that consists of a virtual store with cart management.


## Technologies used

- React-Native

## Requirements

To execute the project it is necessary to have the following requirements installed in the system:

- Node 12.x or later
- Yarn 1.21 or later
- [Android-Sdk](https://react-native.rocketseat.dev/) (To install the app on Android devices)
- [Configured macOS device](https://react-native.rocketseat.dev/ios/macos) (To install the app on iOS devices)

## Running the project

### Cloning the project

```bash
$ git clone https://github.com/felipedmsantos95/gomarketplace
$ cd gomarketplace
```

### Scripts for project execution

Inside the project directory for the first time, you must run the `yarn` command to install the dependencies, so it will be possible to run the following scripts:

#### `yarn json-server --host server_address server.json -p 3333`

To display data on screen, there is a file to be used as a kind of fake API to provide this data. For that, there is a dependency in package.json called json-server, and a file called server.json that contains the data for a `/products` route.


#### `yarn android`

To install the application on devices with Android operating system.

#### `yarn ios`

To install the application on devices with iOS operating system.

#### `yarn start`

Run the Metro Bundle to interact with the application in development mode.
