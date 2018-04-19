# First App

## Environment
  - Must have some version of node and NPM installed 
    
    
      [download/install using brew](https://www.dyclassroom.com/howto-mac/how-to-install-nodejs-and-npm-on-mac-using-homebrew)
    
    
      [download/install on windows](https://nodejs.org/en/download/)
    
    
  - Must have vue cli installed
    - to install on mac or windows simply run the following command command in the terminal/cmd respectively:
    
  ```bash
        npm install -g vue-cli
  ```

## Getting Started
- Once you have cloned the repo, install required packages with npm install:
  
```bash
  npm install
```

- Start the app with:
```bash
  npm run dev
```

## Making changes to the app
- Before making any changes to the app ensure your local version of the master branch is up to date.
- When adding a new feature branch cut a new branch and make sure to adhere to the following naming convention:

```bash
  git branch -b "feat/*description-of-feature*"
```
  
- Similarly for bug fixes:

```bash
  git branch -b "bug/*description-of-bug*"
```
