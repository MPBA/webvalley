# Webvalley

This repository contains the code for the new, upcoming Webvalley website.
Currently targeted for the 2019 edition.


## Beta installation
Note that currently only the development version of Wagtail supports Django>=2, 
hence `nvm` is used to install node to compile static assets.

After installing requirements, navigate to the Wagtail directory:

`cd $VIRTUAL_ENV/src/wagtail`

Install the correct version of `node` via `nvm`:

`nvm install`

Install the packages required by `node` with `npm`:

`npm install`

Compile the binaries needed by Wagtail with:

`npm run build`
