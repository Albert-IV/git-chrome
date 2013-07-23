#git-chrome

## Git Integration Extension for Google Chrome

### Requirements
- [Node.js]() installed and usable through the user's path.  This allows the chrome plugin an API to access localhost
- [git-chrome-node](http://github.com/severeon/git-chrome-node) installed globally.  `sudo npm install git-chrome-node -g`

### Overview

The idea is to have a locally ran API that implements RPC calls.  We can use the different API routes to plug into the power of command line and execute git commands.

Eventually the project will implement oAuth with GitHub, BitBucket, etc. for easy remote git access.