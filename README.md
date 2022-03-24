# Soft UI Dashboard Vue 3 + Vite

Vite is the official build tool that recommanded by Vue.js. It is extremely fast and provides lots enhancements. 


# Development Setup
### Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
- Disable Vetur for this proejct since Vetur does not support Vue3 very well.

### Local
Install dependencies
```bash 
$ yarn
```
Start dev server on localhost
```
$ yarn dev
```
Build for production
```
$ yarn build
```
Start production server on localhost
```
$ yarn preview
```

### Docker
Docker build
```bash 
$ docker build -t softui:latest .
```
Docker run
```
$ docker run -d -p 8080:8080 softui:latest
```
# Quick Config
This template set default port to 8080 on both dev and production. 
- To change vite dev server port, you may edit vite.config.js, to view detailed Vite config [here](https://vitejs.dev/config/)

- To change vite production server port, please change package.json file scripts.preview



# Create New Vue3 + Vite app

```bash
# yarn
yarn create vite my-vue-app --template vue
```
