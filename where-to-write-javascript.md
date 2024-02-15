# Where to Write JavaScript 

JavaScript can be written in three places:

1. **Inline**: Inside an HTML file, you can write JavaScript code inside a `<script>` tag. This is called inline JavaScript.
2. **Internal**: Inside an HTML file, you can write JavaScript code inside a `<script>` tag, but instead of writing the JavaScript code directly inside the `<script>` tag, you can write the JavaScript code inside a separate file and then link to that file using the `src` attribute. This is called internal JavaScript.
3. **External**: You can write JavaScript code in a separate file and then link to that file using the `src` attribute. This is called external JavaScript.

>
> **Note**: JavaScript can also be written in two other places:
> 
> **Console**: You can write JavaScript code in the browser's console. This is called console JavaScript.
> **Server**: You can write JavaScript code on the server. This is called server-side JavaScript.


## Inline JavaScript 

Inline JavaScript is JavaScript code that is written directly inside an HTML file. You can write JavaScript code inside a `<script>` tag. The `<script>` tag can be placed in the `<head>` section or the `<body>` section of an HTML file.

Here is an example of inline JavaScript:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Inline JavaScript</title>
</head>
<body>
    <h1>Inline JavaScript</h1>
    <script>
        console.log('Hello, world!');
    </script>
</body>
</html>
```

In this example, the JavaScript code `console.log('Hello, world!');` is written inside a `<script>` tag. The `<script>` tag is placed inside the `<body>` section of the HTML file. When the HTML file is loaded in a web browser, the JavaScript code will be executed and the message `Hello, world!` will be printed to the console.

## Internal JavaScript

Internal JavaScript is JavaScript code that is written inside an HTML file, but instead of writing the JavaScript code directly inside the `<script>` tag, you write the JavaScript code inside a separate file and then link to that file using the `src` attribute of the `<script>` tag.

Here is an example of internal JavaScript:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Internal JavaScript</title>
    <script src="script.js"></script>
</head>
<body>
    <h1>Internal JavaScript</h1>
</body>
</html>
```

In this example, the JavaScript code is written in a separate file called `script.js`. The `script.js` file contains the following JavaScript code:

```javascript

console.log('Hello, world!');

```

The `script.js` file is linked to the HTML file using the `<script>` tag with the `src` attribute. When the HTML file is loaded in a web browser, the JavaScript code in the `script.js` file will be executed and the message `Hello, world!` will be printed to the console.

## External JavaScript

External JavaScript is JavaScript code that is written in a separate file and then linked to an HTML file using the `src` attribute of the `<script>` tag.              

Here is an example of external JavaScript:

```html
<!DOCTYPE html>
<html>
<head>
    <title>External JavaScript</title>
    <script src="script.js"></script>
</head>
<body>
    <h1>External JavaScript</h1>
</body>
</html>
```

In this example, the JavaScript code is written in a separate file called `script.js`. The `script.js` file contains the following JavaScript code:

```javascript

console.log('Hello, world!');

```

The `script.js` file is linked to the HTML file using the `<script>` tag with the `src` attribute. When the HTML file is loaded in a web browser, the JavaScript code in the `script.js` file will be executed and the message `Hello, world!` will be printed to the console.

## Conclusion

You can write JavaScript code in three places: inline, internal, and external. Inline JavaScript is written directly inside an HTML file. Internal JavaScript is written inside an HTML file, but the JavaScript code is written in a separate file and then linked to the HTML file using the `src` attribute of the `<script>` tag. External JavaScript is written in a separate file and then linked to an HTML file using the `src` attribute of the `<script>` tag.

By the end of this course, you will have a good understanding of JavaScript. You will be able to write JavaScript code and build simple web applications.