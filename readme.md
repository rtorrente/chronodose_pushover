# Chronodose pushover bot

This repository is a fork of https://github.com/PLhery/chronodose_twitterbot for pushover

It leverages https://vitemadose.covidtracker.fr/ to find new available appointments in the "chronodose" section

## Installation

Create a pushover app, and fill .env with the pushover credentials.

You can also tweak some additional available options there.

Then you can
```bash
npm install
npm run build
npm start
```

To run in the background, for instance you can leverage nodemon, pm2 or docker

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)