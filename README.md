# teamxerbutri.cms.maps
Website with a map for the cms of team Xerbutri

## Technicalities

As can be read in the documentation, the website gets its data by reading json files. So we need a local server to serve
these up for us, because the browser won't do this for us.

These files are served up by the Team Xerbutri API, so you need to run the API project. Go to the teamxerbutri.api
project for that. You can first run the website, and next the api.
It will fall back on the teamxerbutri live api if you do not start it and have no local.env file.

## Getting started

Go to the terminal.  
Type: "npm run dev"  
It will start up a localhost and serve the files.

From version 7 onwards you need the API running. Go to the teamxerbutri.api project for that.
In the env.local configure your api host.