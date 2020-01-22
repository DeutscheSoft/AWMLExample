# AWMLExample

This project aims to be an entry point into the UI technology stack consisting of toolkit and AWML of DeusO GmbH. It shows a simple mixing application consisting of 8 channel strips with equalizer, level meter, fader and a title. It uses the very simple default theme "Plain" to not interfere with design issues but to concentrate on paradigms and standards. Various comments inside the source code lead interested developers through some basic features and techniques to give an idea how to build an interface with those libraries.

To investigate clone this repository to your local hard drive, init, sync and update the git submodules (toolkit and AWML) and start a simple webserver in the root directory of the project.

```
git clone git@github.com:DeutscheSoft/AWMLExample.git
cd AWMLExample
git submodule init
git submodule sync
git submodule update
python -m SimpleHTTPServer
```

Point your browser to `localhost:8000` to open the UI. In Firefox or Chrome/Chromium hit `F12` to open the developers tools to investigate the structure. Use your editor to see all comments added to the code. Start with `index.html`, `strip.html`, `local.json` and `styles.css`.

Follow-up to this example could be an investigation of http://demo.deuso.de/ISE2016/index.html
