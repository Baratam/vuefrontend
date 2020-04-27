# real-world-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## build your docker images (subhu6xy6/dolphin is docker hub repo, myVuejs is the image name)
docker build -t subhu6xy6/dolphin:myVuejs .

## run your docker image
docker run -it -p 8080:8080 --rm --name myVuejs1 subhu6xy6/dolphin:myVuejs
