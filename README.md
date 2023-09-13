# Todo App

## Clone Project

```
git clone https://github.com/mmahdik1379/todo.git && cd todo
```

## start json server as api

### Install json server

```
yarn global add json-server
```

### Run json server

```
json-server --watch ./data/db.json
```

## Project setup with npm

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

## Project setup with Nginx Docker

### Build planner image

```
docker build -t planner .
```

### Run planner image as container

```
docker run --rm -it -p 8080:80 planner
```

## Run Project

See [http://localhost:8080/](http://localhost:8080/).
