# vue_crash_todolist

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### To start docker

```
docker build -t todowebapp .
docker run -p 8080:8080 todowebapp
```

### To start docker compose and then build 2 steps commands

```
docker-compose build
docker-compose up
```

### To start docker compose and build 1 step command

```
docker-compose up --build
```