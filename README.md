# vue-webpack-docker

> Template based upon https://github.com/vuejs-templates/webpack to enable hot-relading in docker container.

## Dockerify steps

* Set "poll" to true in ./config/index.js 
* Added "docker-compose.yml" file:
    * Need to set environment variable HOST=0.0.0.0
    * Internal and external ports need to be the same

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080 using docker container
docker-compose up

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
