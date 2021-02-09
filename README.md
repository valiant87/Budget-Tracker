# Budget-Tracker

This app allows user to be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, it should sync the total when brought back online

- [Heroku Live Link]()

---

**Click for demo**
[![Demo](https://img.youtube.com/vi/fMw-ZUlv3Jk/0.jpg)](https://youtu.be/fMw-ZUlv3Jk)

- [Overview](#Overview)
- [Technologies](#Technologies)
- [Credits](#Credits)
- [Questions](#Questions)
- [License](#License)

## Overview

- Offline functionality
- Offline reloads

## Technologies

- Web manifest

  > The web app manifest is a JSON file that tells the browser about your Progressive Web App and how it should behave when installed on the user's desktop or mobile device. A typical manifest file includes the app name, the icons the app should use, and the URL that should be opened when the app is launched.

- Service workers **(sw.js)**

  > A service worker is a script that your browser runs in the background, separate from a web page, opening the door to features that don't need a web page or user interaction.The SW can't access the DOM directly, instead SW can communicate with the pages it controls by responding via post message interface.

- Installation
  To install a service worker check this basic example :
  `self.addEventListener('install', function(event) { // Perform install steps });`

## Credits

- Triology UW BootCamp

  > Provided with the main boiler plate `code`

- [Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers)

  > For study materials, code snipes and documentation. For more documentation(click the link above).

- Heroku
  > Live hosting of the application

## Questions

For any questions, please reach out to [valnimirenco@gmail.com]()
[https://github.com/valiant87]()

## License

This application is covered under the **MIT License**
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Badges

## Badges

<a href="https://img.shields.io/badge/CSS-13.4%25-yellow"><img alt="HTML Usage" src="https://img.shields.io/badge/CSS-13.4%25-yellow"></a> <a href="https://img.shields.io/badge/CSS-4.4%25-purple"><img alt="CSS Usage" src="https://img.shields.io/badge/CSS-4.4%25-purple"></a> <a href="https://img.shields.io/badge/JavaScript-82.2%25-yellow"><img alt="Javascript usage" src="https://img.shields.io/badge/JavaScript-82.2%25-yellow"></a><a href="https://img.shields.io/badge/Backend-Node.js-green"><img alt="Node.js" src="https://img.shields.io/badge/Backend-Node.js-green"></a> <a href="https://img.shields.io/badge/Backend-Express.js-green"><img alt="Express.js" src="https://img.shields.io/badge/Backend-Express.js-green"></a> <a href="https://img.shields.io/badge/Database-MongoDB-yellow"><img alt="database used MongoDB" src="https://img.shields.io/badge/Database-MongoDB-yellow"></a> <a href="https://img.shields.io/badge/Deployment-Heroku-purple"><img alt="deployed using Heroku" src="https://img.shields.io/badge/Deployment-Heroku-purple"></a>
