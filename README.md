# KubiWOZ
The Wizard of Oz Web App for our [KubiLingo](git@github.com:hcrlab/Kubi.git) Experiments

Ensure that you have installed node.js (https://nodejs.org/), Bower (http://bower.io/) and Gulp(https://travismaynard.com/writing/getting-started-with-gulp) before cloning this web app.

After cloning this app for the first time, open a terminal in the base directory for this app and run:

    npm install
    bower install

This will install all dependencies. You will likely encounter several WARN log statements being output from `npm install`. This is ok. 

To build and run the app, run the command `gulp serve` from the base directory of this app. To build the app for deployment, run `gulp` and then copy the contents of the `dist/` directory to the webserver that will be hosting the app.

The app requires that you log in before you can use it. The webapp currently has a test user and password baked into the code (__BAD__), but in the near future will actually require you to log in. Go to https://hcrkubi.firebaseio.com > **Login & Auth** > **Email & Password** and add yourself as a user at the bottom of the page.