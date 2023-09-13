# Todo App

## Clone Project

```
git clone https://github.com/mmahdik1379/todo.git && cd todo
```

## start json server as api

```
yarn global add json-server
```

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

```
docker build -t planner .
```

```
docker run --rm -it -p 8080:80 vue-nginx
```

## Run Project

See [http://localhost:8080/](http://localhost:8080/).
