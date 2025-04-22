# 🌶️ flask-docker-starterkit

A simple boilerplate providing a complete setup to start a new `flask` project

## 🧰 Build the image

To build the docker image, simply open a terminal and run the following command:

```bash
docker-compose build
```

## 🖥️ Run the image

To run the image in a docker container, simply open a terminal and run the following command:

```bash
docker-compose up flaskdockerstarterkit
```

The project will be available on the following URI: `http://127.0.0.1:5000`

## 🐛 Run the image with VSCode debugger

To run the image with the VSCode debugger please follow these steps:

- Run the command `docker-compose up debugger` in your terminal, `debugpy` will wait for the VSCode debugger to attach before running the `flask` server
- Go to VSCode `Run and Debug` Section
- Select the `▶️` button with the option `Python: Remote Attach`

And the `flask` server will run successfully, happy debugging ! 🚀


## 🧪 Run tests

To run the tests, please run the following command in your terminal:

```bash
docker-compose up test-runner
```

## 🕵️ Environment Variables

You need to have a `.env` file containing all the keys and values required.

You can refer to the `.env.example` file

## 🗓️ Features

- Up and running `flask` server
- Containerized application
- Unit tests
- VSCode debugger with hot reload
