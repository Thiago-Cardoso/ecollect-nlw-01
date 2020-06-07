<p align="center">
  <a href="#">
   <img alt="Ecoleta" src="https://github.com/Thiago-Cardoso/ecollect-nlw-01/blob/master/web/src/assets/logo.png?raw=true width="200">
  </a>
</p>

<p align="center">
  <a href="https://github.com/tiagoleal/ecoleta_nlw01">
    <img alt="Current Version" src="https://img.shields.io/badge/version-1.0.0 -blue.svg">
  </a>
  <a href="https://pt-br.reactjs.org/">
    <img alt="" src="https://img.shields.io/badge/React-16.13.1-blue.svg" target="_blank">
  </a>

  <a href="https://nodejs.org/en/">
    <img alt="Node Version" src="https://img.shields.io/badge/node-%3E%3D%2010.14.0-brightgreen" target="_blank">
  </a>
  <a href="https://expressjs.com/pt-br/">
    <img alt="" src="https://img.shields.io/badge/Express-4.17.1-red.svg" target="_blank">
  </a>
  <a href="https://jestjs.io/">
    <img alt="" src="https://img.shields.io/badge/Typescript-3.9.3-blue.svg" target="_blank">
  </a>
  
</p>

## API
![](https://github.com/Thiago-Cardoso/ecollect-nlw-01/blob/master/web/src/assets/ecoleta-api.gif)

## Web

![](https://github.com/Thiago-Cardoso/ecollect-nlw-01/blob/master/web/src/assets/ecoleta-web.gif)

## Mobile
![](https://github.com/Thiago-Cardoso/ecollect-nlw-01/blob/master/web/src/assets/ecoleta-mobile.gif)

## Stack the Project

- **Node**
- **Express**
- **ReactJS**
- **React-native**
- **Expo**
- **Expo-location**
- **TypeScript**
- **SQLite**

## Features

- **Web - Collection point register:** The application allows the
registration of the waste collection point, accoording the coordenate with the GPS along with the location and materials 
that the establishment collects.

- **Mobile:** In the Mobile app allows to search the collection point register based with state and city selected, after this you can click in the types of collect item that you want
and after this points will be show the map and permit to 
click in this company to send mail or WhatsApp message.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You must have installed on your machine:

- Node
- NPM

### Installing

First step is to install the node:

```bash
# Using Ubuntu
$ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
$ sudo apt-get install -y nodejs

# Using Debian, as root
# curl -sL https://deb.nodesource.com/setup_12.x | bash -
# apt-get install -y nodejs

```

For test if the service was installed with succeed, you can run the command for to check de version of Node:

```bash
$ node -v
# Must be have the node version: v12.17.0
$ npm -v
# Must be have the npm version: 6.14.4
```

## First steps

Follow the instructions to have a project present and able to run it locally.
After copying the repository to your machine, go to the project's root ecoleta:

1.  Run server API

```
# Acess server folder:
# run migrate and seed.
$ npm run knex:migrate
$ npm run knex:seed
$ npm run dev

```

2.  Run Web Application

```
# Acess web folder and run:
$ npm start
```

3.  Run the Mobile app (Expo App)

```
# Acess mobile folder and run:
$ npm start
# After scan the Qrcode in the your Expo Mobile App.
```

## Authors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
[<img src="https://avatars1.githubusercontent.com/u/1753070?s=460&v=4" width="100px;"/><br /><sub><b>Thiago Cardoso</b></sub>](https://github.com/Thiago-Cardoso)<br />
