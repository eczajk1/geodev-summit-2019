# geodev-summit-2019
Visualizing Large Spatial Datasets on the Web

This is a demonstration of a 3rd party Vector Tile dataset in MapboxGL. The dataset is the National Bridge Inventory. For more information on how the `mbtiles` file was created, see [this link](https://gist.github.com/eczajk1/55c027b4ad088b7dfa8a113b1171dfc8).

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

### Web App

Once the apps are running, you should be able to view the application by going to `http://localhost:8080`.