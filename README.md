# Selenium-Web-Automation-in-Node-js


This project demonstrates a simple web automation script using [selenium-webdriver](https://www.npmjs.com/package/selenium-webdriver) in Node.js. The script opens Microsoft Edge, navigates to [Bing](https://bing.com), searches for "WebDriver", and waits for the results.

## Prerequisites

- [Node.js](https://nodejs.org/) installed
- Microsoft Edge browser installed
- [Edge WebDriver](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/) available in your system PATH

## Installation

Install dependencies:

```sh
npm install
```

## Usage

Run the script:

```sh
node app.js
```

Or use nodemon for automatic restarts:

```sh
npx nodemon app.js
```

## Project Structure

```
simple/
  app.js
  package.json
```

- `app.js`: Main automation script
- `package.json`: Project dependencies
