[![Stories in Ready](https://badge.waffle.io/codeforhuntsville/Frontier.png?label=ready&title=Ready)](https://waffle.io/codeforhuntsville/Frontier)

# Frontier
Frontier is an app that lets you give it your location and then returns a list of accessible resources nearby. For example, it might tell you the nearest open restaurants, the nearest open gas stations, the nearest public wifi hotspots, the nearest public restrooms, or the nearest open towing/mechanic shops. 

We intend to build Frontier as a hybrid web/mobile HTML app so that it is usable on any device.

# License
[MIT](/LICENSE.txt)

#Setup

1. [install Node.js](https://nodejs.org/download/)
2. [clone the repo](https://help.github.com/articles/fetching-a-remote/)
3. `npm install` to install the project dependencies (dependency modules : `body-parser`, `compression`, `serve-static`, `request`, `config`, `ngrok`, `ejs`)
4. `npm start` to start the server

#Docker

1. [install Docker](https://docs.docker.com/installation/)
2. `make build`
3. `make run GOOGLE_PLACES_API_KEY=supersecretkey`
