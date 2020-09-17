# React gRPC-Web

![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![version](https://img.shields.io/badge/contributors-1-blueviolet) [![version](https://img.shields.io/badge/open%20issues-0-red)](https://github.com/ozuit/react-grpc-web/issues)

This is a demo for using gRPC-Web with the React app. This application is built on top of **create-react-app** and wrapped by [ReactRPC](https://www.npmjs.com/package/reactrpc).

## Image for running app

![Generator Web](./docs/demo.png)

## Get Started

### Prerequisites

- You need to install [Docker](https://www.docker.com/get-started) in order to run the application.

### Installing

- Clone this repo from **[https://github.com/ozuit/react-grpc-web.git](https://github.com/ozuit/react-grpc-web.git)**

### Usage

- Application has been wrapped by Docker so you need only run below command in terminal:

```bash
./scripts/start.sh
```

## Document

Get more information at [wiki](https://github.com/ozuit/react-grpc-web/wiki)

## Support

- If you have any problems with Web Generators don't hesitate to make an [issue](https://github.com/ozuit/react-grpc-web/issues)
- Feel free to folk and submit pull requests
- You can try to modify proto file and re-generated stub client with grpc-web by run following command:
  
```bash
./scripts/render.sh
```

## Authors

- Tan Tong
