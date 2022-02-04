# Vue3-Vite-Vuetify3


### How to create the same configuration:
  1. Install vue-cli: `npm i -g @vue/cli@next` _This installs 5.0.0-rc.2_
  2. Create the project with vue command: `vue create <project_name>` 
     - _vue-cli does not allow capitalization in project name_
  3. Change directory to the newly created Vue project folder and add vuetify：
     - `vue add vuetify`
     - Select the "Vue3 Preview + Vite" _(for project with only vuetify, select "Vue3 Preview")_
     - Follow the prompts
  4. Remove `public/index.html`, since vite use the root `index.html`

### How to create a vue project only with vite:
  - using vite template tool: `npm init vite@latest`
  - Follow the prompt instruction
  - Initial Setup: _Vite doesn't initialize a git repo_
    - initialize Git `git init`
    - Add .gitignore file to the repo, better copy from vue-cli template or existing project
    - Commit changes
    - install packages `npm install`

##### [How to Migrate from Vue CLI to Vite](https://vueschool.io/articles/vuejs-tutorials/how-to-migrate-from-vue-cli-to-vite/)

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
vite serve
```

### Compiles and minifies for production
```
vite build
```

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
