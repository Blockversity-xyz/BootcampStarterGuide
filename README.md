# BootcampStarter


## For Replit users
Go to [Replit.com](https://replit.com/@ReyaneR/BootcampStarter) and clone the BootcampStarter

Whenever you create a new shell make sure you install the Flow CLI on it using this command in the shell 

```sh
sh -ci "$(curl -fsSL https://raw.githubusercontent.com/onflow/flow-cli/master/install.sh)"
```

## For Windows/Linux Users

### Install Node.js

Begin by installing [Node.js](https://nodejs.org/), which is a runtime environment for executing JavaScript outside a web browser.
Npm is Node.js's package manager (It comes with Node and doesn't require any additional install), necessary for managing project dependencies. Download Node.js from their official website, which includes npm.

### Here are the npm packages that are used for this project

#### FLow Client Library (FCL)
Install Flow JavaScript SDK: The Flow JS SDK is a collection of packages that allow you to interact with the Flow blockchain from your React app.
Install it using npm:

```sh
npm install @onflow/fcl @onflow/types
```

#### Chakra
Set up Chakra UI: Chakra UI is a simple, modular, and accessible component library 
that gives you the building blocks to build your React applications. Install Chakra UI by running:

```sh
npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion
```

### Start the server

Use can use the following command to start your local sever and see your app
```sh
npm run dev
```

