# geodev-summit-2019
Visualizing Large Spatial Datasets on the Web

## Install

```
git clone [this repository]
```

## Run

Inside of `./web/index.html`, find and enter your Mapbox API Access Token.

### Docker

Then, to run with Docker, use:
```
docker-compose up
```


### Not Docker
To install and run the tile server:

```
cd ./tile-server
npm install
npm start
```

To run the web front-end:

```
cd ./web
npm install
npm start
```

