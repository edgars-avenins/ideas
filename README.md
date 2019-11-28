# A starter webpack project for React

This is a starter project that uses webpack to transpile and bundle ES6 React code. To use, consider these steps:

* Fork this repo
* Rename your repo according to the app you're building

```sh
git clone https://github.com/[your-account]/[your-app].git
cd [your-app] && npm i
```

To start the development server with a watcher that rebuilds your code, run `npm run dev`. The assets built by webpack are placed in `server/public`. This folder is defined as a static folder in an Express.js server that can be started with `npm run server`.

Additional components should be placed in `client/components`.

## Separate client/server

The boilerplate is also set up to host the client using `webpack-dev-server` with hot module reloading etc. To use this method, in one terminal run:
```sh
npm run client
```
and in the other:
```sh
npm run server
```
The client will be available on http://localhost:8080 and the server on http://localhost:3000. Note that you will still need to manage CORS between the two, as they are on different ports.

Ideas for final project
Voice activated assistant for after graduation staying on track. Look into links(inc. audio visualization)
https://codeburst.io/html5-speech-recognition-api-670846a50e92
https://www.reddit.com/r/LanguageTechnology/comments/a0l3eq/is_there_a_speech_recognition_api_which_matches/
https://www.airtightinteractive.com/2013/10/making-audio-reactive-visuals/
https://therewasaguy.github.io/p5-music-viz/
