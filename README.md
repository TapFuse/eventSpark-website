# Instructions

### Install Harp server
` sudo npm install -g harp`
More info: http://harpjs.com

#### RUN:
Inside project folder run `harp server` this will create a basic HTTP server and compile all *.jade* and *.less* files on the fly. By default you can access the site at `http://localhost:9000/`

#### COMPILE:
Inside project folder run `harp compile ./ ../eventSpark-output` this will create a `eventSpark-output` folder with html file and all the assets required to deploy the site.

#### TEST:
You can run `harp server` inside the `eventSpark-output` folder to test the site locally.

#### DEPLOY:
Commit `eventSpark-output` folder contents to `gh-pages` branch of this repository and sync.
