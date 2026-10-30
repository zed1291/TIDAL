This repo is cause Tidal does not include a version number for their Desktop app anywhere on their page. https://offer.tidal.com/download

I have a cron job on an always on Mac that downloads Tidal, gets the version number, and then updates this repo (if needed), set to run every 6hrs.

This allows me to write a Tidal install script that supports updating, because it can reference the latest version of the app here.
