# Pharmacy Nak Dashboard

## Getting Started
- Install Nodejs from [Nodejs Official Page](https://nodejs.org/en/)
- Open your terminal
- Navigate to the project
- Run `npm install` or `yarn install` if you use [Yarn](https://yarnpkg.com/en/)
- Run `npm run dev` or `yarn serve` to start a local development server
- A new tab will be opened in your browser

You can also run additional npm tasks such as
- `npm run build` to build your app for production
- `npm run lint` to run linting.

## Vuetify
Vuetify is developed exactly according to Material Design spec. Every component is hand crafted to bring you the best possible UI tools to your next great app. The development doesn't stop at the core components outlined in Google's spec. Through the support of community members and sponsors, additional components will be designed and made available for everyone to enjoy.


## Vuex

Vuex is a state management pattern + library for Vue.js applications. It serves as a centralized store for all the components in an application, with rules ensuring that the state can only be mutated in a predictable fashion. It also integrates with Vue's official [devtools](https://github.com/vuejs/vue-devtools) extension to provide advanced features such as zero-config time-travel debugging and state snapshot export / import.

## Vue-cli

We used the latest 3.x [Vue CLI](https://github.com/vuejs/vue-cli) which aims to reduce project configuration
to as little as possible. Almost everything is inside `package.json` + some other related files such as
`.babel.config.js`, `.eslintrc.js` and `.postcssrc.js`.

Let us know your thoughts below. And good luck with development!

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions


[<img src="https://pbs.twimg.com/profile_images/900908683927982080/GWykKJ7r_400x400.jpg" width="60" height="60" />](https://www.creative-tim.com/product/vuetify-material-dashboard)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/html.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/react.svg" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-react)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/vuejs.png" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-dashboard-pro)
[<img src="https://s3.amazonaws.com/creativetim_bucket/github/angular.png" width="60" height="60" />](https://www.creative-tim.com/product/material-dashboard-pro-angular2)


Vuetify | Vue | React | Angular | HTML |
| --- | --- | --- | --- | --- |
| [![Vuetify Material Dashboard](https://s3.amazonaws.com/creativetim_bucket/products/100/original/opt_md_vuetify_thumbnail.jpg)](https://www.creative-tim.com/product/vuetify-material-dashboard-pro) | [![Vue Material Dashboard](https://s3.amazonaws.com/creativetim_bucket/products/81/original/opt_md_vue_thumbnail.jpg)](https://www.creative-tim.com/product/vue-material-dashboard) | [![Material Dashboard React](https://s3.amazonaws.com/creativetim_bucket/products/71/original/opt_mdr_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-react)  | [![Material Dashboard Angular](https://s3.amazonaws.com/creativetim_bucket/products/53/original/opt_md_angular_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard-angular2) | [![Material Dashboard HTML](https://s3.amazonaws.com/creativetim_bucket/products/50/original/opt_md_thumbnail.jpg)](https://www.creative-tim.com/product/material-dashboard)

## File Structure

Within the download you'll find the following directories and files:

```
vuetify-material-dashboard
├── ISSUE_TEMPLATE.md
├── LICENSE.md
├── README.md
├── babel.config.js
├── cypress.json
├── jest.config.js
├── package.json
├── postcss.config.js
├── public
│   ├── favicon.ico
│   ├── img
│   └── index.html
├── src
│   ├── App.vue
│   ├── assets
│   │   └── vuetify.svg
│   ├── components
│   │   ├── base
│   │   │   └── Card.vue
│   │   ├── core
│   │   │   ├── AppBar.vue
│   │   │   ├── Drawer.vue
│   │   │   ├── Filter.vue
│   │   │   ├── Footer.vue
│   │   │   └── View.vue
│   │   ├── helper
│   │   │   └── Offset.vue
│   │   └── material
│   │       ├── Card.vue
│   │       ├── ChartCard.vue
│   │       ├── Notification.vue
│   │       └── StatsCard.vue
│   ├── main.js
│   ├── plugins
│   │   ├── axios.js
│   │   ├── base.js
│   │   ├── chartist.js
│   │   ├── components.js
│   │   ├── index.js
│   │   └── vuetify.js
│   ├── router
│   │   ├── index.js
│   │   └── paths.js
│   ├── store
│   │   ├── actions.js
│   │   ├── getters.js
│   │   ├── index.js
│   │   ├── modules
│   │   │   ├── app
│   │   │   │   ├── mutations.js
│   │   │   │   └── state.js
│   │   │   └── index.js
│   │   ├── mutations.js
│   │   └── state.js
│   ├── utils
│   │   └── vuex.js
│   └── views
│       ├── Dashboard.vue
│       ├── Icons.vue
│       ├── Maps.vue
│       ├── Notifications.vue
│       ├── TableList.vue
│       ├── Typography.vue
│       ├── Upgrade.vue
│       └── UserProfile.vue
├── tests
│   ├── e2e
│   │   ├── plugins
│   │   │   └── index.js
│   │   ├── specs
│   │   │   └── test.js
│   │   └── support
│   │       ├── commands.js
│   │       └── index.js
│   └── unit
│       └── example.spec.js
├── vue.config.js
└── yarn.lock
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

