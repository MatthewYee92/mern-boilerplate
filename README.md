# MERN Boilerplate
MongoDB Express.js React.js Node.js

A Full MERN Stack Boilerplate for Web Apps. Includes a local authentication system using passport. User is given a simple profile with Full Name and Profile Picture. User is also able to reset password and username case. Intent is to make this repo public and for shared use. I intend on keeping the repo up to date as well. If you would like to help contribue, feel free to make a pull request. 


## Quick Start

#### Setup

```bash
npm install

brew tap mongodb/brew
brew install mongodb-community
```

Start the database
```bash
brew services start mongodb-community
# or
mongod
```

#### for Development

Start the client
```bash
npm run dev
```

Start the server
```bash
npm start
```

#### for Production

```bash
npm run prod
```

## Setup Instructions

To setup your own project, you will need to copy the contents of this project into a new repo.
You will need to update the content in these files to names of your project and yourself:

* package.json: name, version, description, repository, author, bugs, homepage
* LICENSE: (update to your preferred license)
* client/index.html: description and title
* this README.md

This is also a good time to go through the included libraries to add or remove features that you want.

After this you can commit the files into a new repository and push up to your github.
You can now start updating files in your client to begin working on your own project!

## Features

* Webpack conveniently bundles your code for you.
* Babel lets you use ES6/7 features.
* CSS pre-processor setup for LESS and SASS lets you keep your styles clean and organized.
* ESLint helps you maintain a high level of code quality.
* Jest and Enzyme give you a robust testing frame work to make sure your code works.

## Code Structure

```
- client
  - api
  - assets
    - images
    - icons
  - components
    - atoms
    - molecules
    - organisms
    - templates
    - pages
    - environment
  - hooks
  - store
    - actions
    - reducers
    - thunks
    - tests
  - styles
  - utils
- server
  - config
  - database
  - routes
- scripts
```



