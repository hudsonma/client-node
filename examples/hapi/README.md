# SMART Client With HAPI 17
This is an example of how the SMART Client can be used with HAPI 17

## Install and Run
From your project `cd` into the example folder and start it:
```sh
cd examples/hapi
npm i
npm start
```
Then open http://localhost:3000 to try it.

NOTE: This sample app works with the SMART Dev Sandbox and HSPC. If you want to
try this against other servers you might have to register it there, obtain a
`clientId` and set it [here](index.js#L9) before starting the app.