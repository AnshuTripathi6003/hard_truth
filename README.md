# Hard Truth

This code is for the APIs of Hard truth project which I started to mark the videos present on youtube to rate the news channels as how pro or anti government they are. So that a user can define from the video if the channel is trying to manipuate them or not.
Clone Repo :

$ git clone https://github.com/AnshuTripathi6003/hard_truth.git

On windows install below module

$ npm install --global --production windows-build-tools

Install node modules

$ npm install

Refer to this Article to get your API keys for google: https://developers.google.com/youtube/v3/getting-started

Install mysql and sequalize on your machine.
Add values in .env

$ export NODE_ENV=development

$ export MYSQL_URI_LOCAL=<mysql-url>

$ export API_KEYS=<google_api_keys>

Run server

$ npm run start:dev
