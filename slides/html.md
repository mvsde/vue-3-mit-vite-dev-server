---
layout: two-cols
---

# index.html

## Vue CLI

```html {all|12}
<!DOCTYPE html>
<html lang="de">

  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="…">
    <title>Vue App</title>
  </head>

  <body>
    <div id="app"></div>
    // Built files will be auto injected
  </body>

</html>
```

::right::

<div class="mt-14" />

<v-click>

## Vite

</v-click>

<v-after>

```html {12,13}
<!DOCTYPE html>
<html lang="de">

  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="…">
    <title>Vue App</title>
  </head>

  <body>
    <div id="app"></div>
    <script type="module" src="/src/main.js">
    </script>
  </body>

</html>
```

</v-after>

<!--
* HTML vom "public"-Ordner zum "root" verschieben
-->
