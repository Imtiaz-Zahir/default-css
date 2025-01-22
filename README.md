# Default CSS

A lightweight CSS stylesheet for rendering **Quill.js** output. Designed to ensure that Quill's generated HTML content is styled consistently, while working seamlessly with global frameworks like **Tailwind CSS** and other default styles.

## Features

- Ensures Quill.js rendered HTML is styled properly and consistently.
- Integrates well with other CSS frameworks like **Tailwind CSS** or any global styles.
- Uses modern `rem` and `em` units to ensure scalability and responsiveness.
- Simple and lightweight, adding minimal extra CSS for the best user experience.

---

Here’s an updated section that includes additional installation methods:  

---

## Installation

### NPM
Install the package via NPM:

```bash
npm install default-css
```

### Yarn
Install the package using Yarn:

```bash
yarn add default-css
```

### PNPM
Install the package using PNPM:

```bash
pnpm add default-css
``` 

--- 

## Usage

### Import in JavaScript/TypeScript File:
To apply the default styles globally, simply import the `style.css` file:

```javascript
import 'default-css/style.css';
```

### Import in a CSS/SCSS File:
If you are using a custom CSS or SCSS file, include the package:

```css
@import 'default-css/style.css';
```

### Add as a `<link>` in HTML:
After installing the package via NPM, link it directly in your HTML:

```html
<link rel="stylesheet" href="./node_modules/default-css/style.css">
```

### React Integration

To use **Default CSS** in a React project, simply import the `style.css` file in your main JavaScript/TypeScript file:

```javascript
import 'default-css/style.css';

function App() {
  return (
    <div className="App">
      <h1>Quill.js Output with Default CSS</h1>
      <div id="editor"></div>
      <div id="output" className="default-css">
        {/* Quill.js content will be styled here */}
      </div>
    </div>
  );
}

export default App;
```

### Vue Integration

In a Vue.js project, include the **Default CSS** stylesheet globally by importing it in your `main.js` or `main.ts`:

```javascript
import 'default-css/style.css';

new Vue({
  render: h => h(App),
}).$mount('#app');
```

In your Vue component, you can then use the Quill.js output container:

```html
<template>
  <div id="output" class="default-css">
    <!-- Quill.js content will be styled here -->
  </div>
</template>

<script>
export default {
  mounted() {
    // Quill.js setup logic goes here
  },
};
</script>
```

### Angular Integration

In an Angular project, import **Default CSS** in your `angular.json` file to apply globally:

```json
"styles": [
  "src/styles.css",
  "node_modules/default-css/style.css"
]
```

Then, in your component template, use the Quill.js output container:

```html
<div id="output" class="default-css">
  <!-- Quill.js content will be styled here -->
</div>
```

---

## Example Integration with Quill.js Output

Here’s an example of how **Default CSS** will work with **Quill.js** to style its output and ensure it integrates well with **Tailwind CSS** or other global styles.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quill.js with Default CSS</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.0.3/dist/tailwind.min.css" rel="stylesheet">
  <link rel="stylesheet" href="./node_modules/default-css/style.css"> <!-- Import default styles -->
</head>
<body>
  <div class="container mx-auto p-4">
    <h1 class="text-3xl font-bold mb-4">Quill.js Output with Default CSS</h1>
    <div id="editor"></div>
    <div id="output" class="mt-4 default-css">
      <!-- Quill.js will render here, and its output will be styled by default-css -->
    </div>
  </div>
</body>
</html>
```

In the above example:
- **Tailwind CSS** is used for the general layout.
- **Default CSS** styles Quill's rendered output within the `#output` div, ensuring consistency.

---

## Key Features

- **Quill.js Styling**: Ensures that Quill’s output is styled correctly and integrates smoothly into your existing design system.
- **Responsive & Scalable**: Uses `rem` and `em` units for typography, ensuring good responsiveness across devices.
- **Works with Tailwind CSS**: Quill’s generated HTML content will inherit the correct default styles, while still working seamlessly with Tailwind or other CSS frameworks.
- **Minimalistic Approach**: Adds minimal extra CSS to make sure Quill’s output looks polished, without overriding your global styles.

---

## Contributing

We welcome contributions! If you find a bug or have a feature request, please open an issue or submit a pull request.

---

## License

This project is licensed under the **ISC License**. See the [LICENSE](LICENSE) file for more details.

---

## Keywords

`Quill.js Styles`, `Quill.js Output`, `CSS Framework`, `Responsive CSS`, `Tailwind CSS`, `Default Styles`, `Global Stylesheet`, `rem and em CSS`, `Lightweight CSS Package`.

---

Integrate **Default CSS** with Quill.js and your favorite CSS framework to ensure your content is styled properly across any platform.
