# _Al Roker 2 Electric Boogaloo_

#### By _**Chris DePastene, Chris Nakayama, Ebru Rice, Jack Skelton, Phil Curran**_

## Github Pages Link

[Al Roker 2 Electric Boogaloo Github Pages](https://ebruri.github.io/TeamWeekWeatherApp/)

## Technologies Used

- _HTML_
- _CSS & Bootstrap_
- _Javascript & jQuery_
- _NPM & Webpack_

## Description

1. This application will provide the weather from a selected city.
2. Display weather forecast info for current day.
3. Display weather forecast info for 5 days.
4. It will display low and high temp range.
5. It will display Weather Forecast Rain/Sun/Snow/Wind.
6. A clean simple homepage with a search function for weather.

## Setup/Installation Requirements

#### Dependencies & Versions Used

"devDependencies": "@babel/core": "^7.6.4", "@babel/plugin-transform-modules-commonjs": "^7.6.0", "clean-webpack-plugin": "^3.0.0", "css-loader": "^3.2.0", "dotenv-webpack": "^7.0.3", "eslint": "^6.3.0", "eslint-loader": "^3.0.0", "html-webpack-plugin": "^3.2.0", "style-loader": "^1.0.0", "webpack": "4.39.3", "webpack-cli": "^3.3.8", "webpack-dev-server": "^3.8.0" }, "dependencies": { "bootstrap": "^4.5.0", "jquery": "^3.5.1", "popper.js": "^1.16.1"

- It is HEAVILY encouraged to clone the repo or copy/paste the values in the package.json and webpack.config files in order to ensure compatibility - the following instructions assume this has not been done"
- After installing the above technologies, begin by using Git Bash (or another terminal program) to run $ npm install at the root directory of your project file
- If you are a Mac user, replace the & in package.json with a ; "start": "npm run build & webpack-dev-server --open --mode=development",
- Creat a .gitignore file and write in the following:
node_modules/ .DS_Store dist/ coverage/ .env
- Sign up for a free account and secure an API KEY at: https://openweathermap.org/api.
- In your root directory, Make a .env file (and BE SURE it is added to gitignore below coverage/) and enter API_KEY = {YOUR API KEY HERE} - NOTE: It is crucial to complete this step and be sure your API key is never directly referenced in your javascript file. 
This API KEY will be from: https://openweathermap.org/api.  
- This program requires an API key for GOOGLE to be installed in the HTML code in order to search cities properly. Secure an API Key for GOOGLE Maps and install key inside line 36 on index.html.
- Update your package.json by running $ npm run build in your terminal of choice and verifying there are no errors
- Run $ npm run start to bring up a live server in your browser (Google Chrome preferred)

## Known Bugs

- _No Known Issues_

## Contact 

_Please contact one of us if you run into any issues or have questions, ideas or concerns:_
_[skelton.jt9@gmail.com, cnakayam@gmail.com, cdepastene@gmail.com, ebruerenb@gmail.com, pecurran@hotmail.com]_

## License

MIT

Copyright (c) _2022_Chris DePastene, Chris Nakayama, Ebru Rice, Jack Skelton, Phil Curran_
