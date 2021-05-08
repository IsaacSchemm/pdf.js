# PDF.js

This is a fork of PDF.js which works with SeaMonkey 2.49.x and Firefox 52 ESR. It may also work in Pale Moon.

Note that any "testing" that exists for this fork is very limited, and some features may not work. Before filing a bug on this fork, first check to see if the problem occurs on the newest version of Firefox - if it does, file the bug on Mozilla's upstream repository instead.

For more information about pdf.js, see: https://github.com/mozilla/pdf.js

## Getting the Code

To get a local copy of the current code, clone it using git:

    $ git clone git://github.com/IsaacSchemm/pdf.js-seamonkey.git
    $ cd pdf.js

Next, install Node.js via the [official package](https://nodejs.org) or via
[nvm](https://github.com/creationix/nvm). You need to install the gulp package
globally (see also [gulp's getting started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md#getting-started)):

    $ npm install -g gulp-cli

If everything worked out, install all dependencies for PDF.js:

    $ npm install

## Building PDF.js

To build the SeaMonkey extension, run:

    $ gulp seamonkey

## Installing

You can get the latest release of this fork from the
[releases page on GitHub](https://github.com/IsaacSchemm/pdf.js-seamonkey/releases)
or from [addons.thunderbird.net](https://addons.thunderbird.net/en-US/seamonkey/addon/pdf-js-for-seamonkey/).