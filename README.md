# Todo app with NextJs, ExpressJs and MongoDb

## Features
This project has the following feature:
- register
- login
- dark mode
- multilang app
- zustand for handling state
- mongodb for database

## Installation
First, clone the project then. It uses submodules (to separate the backend service with the frontend). So run these commands after cloning:
- git submodule init
- git submodule update

## Run
### Development mode
For the development mode, you need to have Node 18 or higher installed in your pc. To install dependencies for both services:
```bash
    yarn
```

Configure .env (copy the .env.example and change the value)

To run
```bash
    yarn dev
```

The backend is exposed on 5999, and the front on 5998.

### Using docker
you just need to run
```bash
    docker compose up --build
```

Now you are good to go.