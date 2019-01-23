# React Calculator Casio

A calculator that provides the essential arithmetic operations, an expression builder, and a complete history of all expressions.

# Online Demo

 https://codesandbox.io/s/github/saeedafroozi/react-casio-calculator


The application is composed of the following components:


* Calculator - The primary (root) component for managing all Calculator and underlying component state.

* Display - Displays the calculator input, expression, and history

* Keypad - Used to input operands as well as execute various operations against those operands


The application makes use of the following domain services:

* CalculatorEngine - A domain service that encapsulates calculator logic

Domain Service Diagram
![Domain Service Diagram](https://user-images.githubusercontent.com/33935506/34460977-173787e4-ee27-11e7-8655-0223a92a315d.png)

Features:

* Add
* Subtract
* Multiply
* Divide
* Toggle Sign
* Expression Builder
* Sqrt
* Percent
* History
  * Add History
  * SubTrack history
  * Clear History
* Clear current value and expression(without Clear History)
* Turn On And Clear(without Clear History)
* Turn Off

This project also demonstrates:

* a typcial React project layout structure
* babel setup and configuration
* webpack setup and configuration
* SCSS setup and configuration

main feature(Customize For Flix Bus):
this Calculator Is Customized To be similar as possible as to Casio Calculator So It Has Some Main Feature:
* The Appearance is very similar To Sl-300sv but in some Cases maybe the font or sizes not be equal
  * 1-every three digits it has a separator
  * 2-you can define the number of the digit at the beginning of CalCulatorEnginComponent 
  * 3-it Shows The Error Or Memory sign
  * 4-it shows a little expression To prevent Confusing in Calculate
* the functionality is very tried to be same for instance :
* after cross between 2*2 by pressing equally you can repeat the cross again and again
* after cross 2*2 if you press * it shows the equal and wait for another operator
* you can change the operator after pressing 
* you can use memory in every Operation


## Developed With

* [Visual Studio Code](https://code.visualstudio.com/) - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [Babel](https://babeljs.io/) - A transpiler for javascript
* [Webpack](https://webpack.js.org/) - A module bundler
* [SCSS](http://sass-lang.com/) - A css metalanguage
* [Bootstrap 4](https://getbootstrap.com/) - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
* [Surge] - Static web publishing for Front-End Developers

**** I've test this app Only on chrome and IE 

---



## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software is required to be installed on your system:

* Node 8.x
* Npm 3.x

Type the following commands in the terminal to verify your node and npm versions

```bash
node -v
npm -v
```

### Install

Follow the following steps to get development environment running.


* Install node modules

   ```bash
   cd casio
   npm install
   ```

### Build

* Build application



  ```bash
  npm run build
  ```

* Build application and start watching for changes


  ```bash
  npm run build:watch
  ```



### Run

* Run start

  This will run the _'serve'_ npm task

  ```bash
  npm start
  ```

* Run webpack dev server

  ```bash
  npm run serve:dev
  ```

* Alternatively run live-server (simple development http server with live reload capability)

  ```bash
  npm run serve
  ```

---



## Authors

* **Saeed Afroozi** - *Initial work* - (https://github.com/saeedafroozi)
