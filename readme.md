you can download the npm.css here [npm-css](https://github.com/JuanMolina2001/npm-markdown-css/blob/master/npm.css)

you can see the demo here [Demo](https://juanmolina2001.github.io/npm-markdown-css/)
## Usage
```html
  <link rel="stylesheet" href="./npm.css">
   <!-- you can use the parsing library you want  -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/marked/13.0.2/marked.min.js"></script>
    <!-- the container element must be called markdown-body -->
      <div class="markdown-body">

    </div>
    <script>
        document.querySelector('.markdown-body').innerHTML = marked.parse('## this is a markdown text')
    </script>
```
