# Installing Tailwind CSS as a Vite plugin

### Install Tailwind CSS
```bash
npm install tailwindcss @tailwindcss/vite
```

### Configure the Vite plugin
```ts
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})
```

### Import Tailwind CSS

```CSS
@import "tailwindcss";
```

### Start using Tailwind in your HTML

```HTML
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="/src/style.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```
