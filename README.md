elm-webcam-example
==================
This repository contains a minimal implementation of a webcam feed inside an 
elm application.  

A blog article detailing the implementation can be found here:  
[Blog Article]()

An example of this code running in your browser can be found here:  
[Demo page](https://maartentegelaers.me/elm-webcam-example/)

Prerequisites
-------------
The code is written for Elm 0.17 and use of the elm-lang/html library.

In order to run the code locally you will have to run a simple HTTPS server,
for example with python. 

Furthermore, in order for the code to work you will need to use a browser that
supports [navigator.getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/Navigator/getUserMedia)
Most modern browser will support this however, so this should not be a problem.

Build Instructions
------------------
Run the following command from the root of this project:

```bash
elm make --output target/WebcamApp.js src/WebcamApp.elm
```

then open index.html through a webserver.
