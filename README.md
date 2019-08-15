# vue-browser

`$ vue create <project>` merge 

vue CLI v3.6.2  
? Please pick a preset: `Manually` select features  
? Check the features needed for your project: `Babel, Router` 
? Use history mode for router? (Requires proper server setup for index fallback in production) Yes
? Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In dedicated config files
? Save this as a preset for future projects? No  

`$ cd vue-browser`  
`$ yarn serve`  

### gh-pages

[![NPM](https://nodei.co/npm/gh-pages.png?downloads=true&stars=true)](https://nodei.co/npm/gh-pages/)  
> Publish files to a gh-pages branch on GitHub (or any other branch anywhere else).

`$ npm install gh-pages --save-dev` 


vue.config.js
```js
module.exports = {
    publicPath: 'vue-browser'   
}
```

package.json
```js
"deploy": "npm run build && gh-pages -d dist"
```


`$ npm run deploy`

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
