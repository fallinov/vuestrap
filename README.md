# Projet Vuestrap

## Environnement de développement

* Node.js 10
* Vue CLI 3

### Installation Vue Cli
```
yarn global add @vue/cli

vue --version 
```

Créer un nouveau projet : https://cli.vuejs.org/guide/creating-a-project.html

```
vue create hello-world
```


## Commandes d'installation et développement
### Project setup
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


## Liens utiles

* https://css-tricks.com/how-to-import-a-sass-file-into-every-vue-component-in-an-app/
* https://vuex.vuejs.org/guide/plugins.html
* https://cli.vuejs.org/guide/html-and-static-assets.html#static-assets-handling

## Astuces

### CSS Lien vers ressources avec ~ 

```css
@font-face {
  font-family: "Roboto Light";
  src: url("~@/assets/fonts/Roboto-Light.woff2") format("woff2");
}
```
