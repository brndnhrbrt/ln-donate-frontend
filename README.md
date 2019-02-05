# ln-donate-frontend

This is a sample implementation of [https://github.com/brndnhrbrt/ln-donate-node](https://github.com/brndnhrbrt/ln-donate-node)

## Getting Started

1. Setup the ln-donate-node server
2. Import donateButton.js and donateButton.css
3. Add the desired HTML from the template.html file
4. Input your ln-donate-node server's url in the HTML and JavaScript code


## Example

```
<html>
    <head>
        <script src="./donateButton.js"></script>
        <link rel="stylesheet" type="text/css" href="./donateButton.css">
    </head>
    <body>
        <div class="lnd-donate-container">
            <h3>Preset amount</h3>
            <img id="lnd-donate-image" class="lndHideImage" src="http://YOUR_URL_HERE:3000/">
            <br>
            <button class="lnd-donate-button" onclick="lndBtnPressed()">Donate</button>
        </div>
    </body>
</html>
```

## Live Example

[http://brndnhrbrt.github.io/donate.test.html](http://brndnhrbrt.github.io/donate.test.html)