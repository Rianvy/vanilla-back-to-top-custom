# Examples

<img src="https://github.com/Rianvy/vanilla-back-to-top-custom/examples/images/default.png" width="66"/> (default)<br/>
```html
<script>addBackToTop()</script>
```


----------


<img src="https://github.com/Rianvy/vanilla-back-to-top-custom/examples/images/coral.png" width="66" /><br/>
```html
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(255, 82, 82)',
  textColor: '#fff'
})</script>
```


----------


<img src="https://github.com/Rianvy/vanilla-back-to-top-custom/examples/images/smaller.png" width="57" /><br/>
```html
<script>addBackToTop({
  diameter: 40,
  backgroundColor: '#ddd',
  textColor: 'red'
})</script>
```


----------


<img src="https://github.com/Rianvy/vanilla-back-to-top-custom/examples/images/rectangle.png" width="121" /><br/>
```html
<script>addBackToTop({
  backgroundColor: '#fff',
  innerHTML: 'Back to Top',
  textColor: '#333'
})</script>
<style>
  #back-to-top {
    border: 1px solid #ccc;
    border-radius: 0;
    font-family: sans-serif;
    font-size: 14px;
    width: 100px;
    text-align: center;
    line-height: 30px;
    height: 30px;
  }
</style>
```


----------


<img src="https://github.com/Rianvy/vanilla-back-to-top-custom/examples/images/different-arrow.png" width="72" /><br/>
```html
<script>addBackToTop({
  backgroundColor: '#ffda0c',
  innerHTML: '<svg viewBox="0 0 24 24"><path d="M4 12l1.41 1.41L11 7.83V20h2V7.83l5.58 5.59L20 12l-8-8-8 8z"/></svg>',
  textColor: '#96071f'
})</script>
```
