---
layout: two-cols
---

# package.json

## Vue CLI

```json {all|3,4,12}
{
  "scripts": {
    "dev": "vue-cli-service serve",
    "build": "vue-cli-service build"
  },
  "dependencies": {
    "vue": "^3.1.5",
    "vue-router": "^4.0.10",
    "vuex": "^4.0.2"
  },
  "devDependencies": {
    "@vue/cli-service": "^4.5.13",
    "@vue/compiler-sfc": "^3.1.5",
    "sass": "^1.37.5"
  }
}
```

::right::

<div class="mt-14" />

<v-click>

## Vite

</v-click>

<v-after>

```json {3,4,12,15}
{
  "scripts": {
    "dev": "vite",
    "build": "vite build"
  },
  "dependencies": {
    "vue": "^3.1.5",
    "vue-router": "^4.0.10",
    "vuex": "^4.0.2"
  },
  "devDependencies": {
    "@vitejs/plugin-vue": "^1.3.0",
    "@vue/compiler-sfc": "^3.1.5",
    "sass": "^1.37.5",
    "vite": "^2.4.4"
  }
}
```

</v-after>

<!--
* Komplexität abhängig von webpack-spezifischen Funktionen
-->
