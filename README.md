# Eats

# Description
The Eats is the software automation of the current feeding system so as to make it scalable through enabling access to all people without having to incur extra cost. The solution will also serve as a central place where all meal information is stored both for people and vendors. Vendors can manage meals and view feedback. People can conveniently pre-order meals without the fear that a particular favorite meal is finished.


## Technology Stack
 + React: `A JavaScript library for building user interface`
 + Redux: `A predictable state container for JavaScript apps`
 + Node: `An open-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side.`
 + Yarn: `A package manager for JavaScript`

### Getting Started
Here is how to get a copy of the project up and running on your local machine for development and testing purposes.

# Installation

### Prerequisites
* You will need to have npm, the best way to install npm is to install node using the [node.js installer](https://nodejs.org/en/download/), npm is installed as part of node.

* Clone this repository by running the command
`git clone https://github.com/andela/AndelaEatsUI.git`

* After successfully cloning the project:
`cd AndelaEatsUI/client`

* To Install dependencies.
`yarn install`

* You will require to create an alias for andelaeats-dev.andela.com in your /etc/hosts which you can access by running this command
  ```sudo vim /etc/hosts``` which opens your /etc/hosts for editing using vim.
  To edit it, get into insert mode by pressing ```i``` key and put these
   ```127.0.0.1       andelaeats-dev.andela.com``` after the last line.

*  Setup your .env variables (ask the other team members for the keys). An example is available in the env.example file.

### Starting the app
* To start the app locally run the following commands
`yarn build && yarn dev`

## Testing
* For Component test
`yarn test`
