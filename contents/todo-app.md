# todo app

## table of contents
1. [project setting](#project-setting)
1. [vue router setting](#vue-router-setting)

`Vue.js 3.0` 버전에서는 어떤 점이 달라졌는지 TODO 앱을 만들면서 알아보겠습니다.

## project setting

```bash
npx @vue/cli create vue3-todo-app
```


## vue router setting
Vue 3 Preset은 `vue-router` 및 `vuex`를 직접 설치해야 함

```bash
npm install vue-router@4.0.0-beta.5
```

```
src/router/index.js
```

```js
import { createRouter, createWebHistory } from 'vue-router'

const routes = [{
  
}]
const router = createRouter({
  history: createWebHistory(process.env.BASE_URL),
  routes,
})

export default router
```



