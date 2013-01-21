#Dillinger (Stackato-ready)!

.. forked from https://github.com/joemccann/dillinger

[Dillinger] is a cloud-enabled HTML5 Markdown editor.

  - Type some Markdown text in the left window
  - See the HTML in the right
  - Magic

## Deploying to Stackato

    $ git clone git://github.com/Stackato-Apps/dillinger.git
    $ cd dillinger
    $ stackato push -n

## Deploy locally

    $ git clone git://github.com/Stackato-Apps/dillinger.git
    $ cd dillinger
    $ npm i
    $ mkdir -p public/files
    $ mkdir -p public/files/md && mkdir -p public/files/html
    $ node app.js

***
###Dropbox integration:

Create your app with dropbox:  https://www.dropbox.com/developers/apps

Add your app key and secret in `plugins/dropbox/dropbox-config.json`

###Github integration:

Create your app with Github: https://github.com/settings/applications/new

Add your app id and secret in `plugins/github/github-config.json`

[dillinger]: http://dillinger.io 

