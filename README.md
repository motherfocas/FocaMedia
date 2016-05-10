Ionic FocaMedia
=====================

A simple movile app for your media library.

Development
=====================

In order to run the proyect in your computer you'll need to install the `ionic` binaries.

```bash
$ sudo npm install -g ionic cordova
```

Then, make sure you have google chrome installed and the binary `google-chrome` exists, if not, simply run:

```bash
$ sudo ln -s /usr/bin/google-chrome-stable /usr/bin/google-chrome
```

We're almost ready, clone the proyect and add the browser as a platform for the project:
```bash
$ git clone https://github.com/Alvaroctal/FocaMedia.git
$ cd FocaMedia
$ ionic platform add ionic
```

Now, launch the project:
```bash
$ ./FocaMediaClient.sh
```
You'll need to relaunch the project with every change you make.
