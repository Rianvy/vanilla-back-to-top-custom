# Install

If you don't want to rely on [unpkg.com](https://unpkg.com/#/about), save [the file](https://github.com/Rianvy/vanilla-back-to-top-custom/blob/main/dist/vanilla-back-to-top.min.js) to your project and serve it from your server:
```html
<script src="/assets/vanilla-back-to-top.min.js"></script>
<script>addBackToTop()</script>
```

<a id="#import"></a>You can also install the package via npm and import it into your bundle:
```bash
npm install --save vanilla-back-to-top-custom
```
```js
import { addBackToTop } from 'vanilla-back-to-top'
addBackToTop()
```
