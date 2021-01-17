# Nuxt Fundamentals


Working with Nuxt bring lots of advantanges:

* __Automatic__ & easy Dynamic Routering;
* __Vuex__ Structure Use;
* __Advanced__ Project Structure;
* __Automatic__ Lazy loading/Code spliting;
* __Ability__ to set a global css into the nuxt.config file;
* __Ability__ to add/remove components into the layout folder;

Notes:

* To set dynamic routering into a nuxt app we can create the page(file) using _ (underline).
* To add links we must use the nuxt-router; 
* Its recommended to use not the path but the name of the page the will be displayed for example, if you have a page inside a folder called posts, you can call it into the nuxt-router using 'posts-nameofthepage'

*using vuex into a nuxt project seems to be the same way. we can use the classic mode (just a index.js file) or add the modules of the vuex structure.*

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
