# taskbox

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

### Run your unit tests
```
yarn test:unit
```

### Lints and fixes files
```
yarn lint
```

### Deploy to GitHub Pages
```
yarn gh-pages-deploy
```
See [deploy to github pages](https://dev.to/rolanddoda/deploy-to-github-pages-like-a-pro-with-github-actions-4hdg)

### Run Storybook
```
yarn storybook
```

### Build Storybook
```
yarn build-storybook
```

### Deploy Storybook to GitHub Pages

Requires vue.config.js with content
```
module.exports = {
  publicPath: '/taskbox/'
}
```

```
yarn deploy-storybook
```

### View deployed storybook on GitHub Pages
```
open https://stuheiss.github.io/taskbox
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
