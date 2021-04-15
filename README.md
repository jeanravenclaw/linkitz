# linkitz

A simple multi-purpose link website.

To create a new link, paste this code into a `file.html`. Change some links and titles to make it work.

```html
<!DOCTYPE html>
<html>
    <head>
        <!-- title -->
        <title>linkitz</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <!-- favicon -->
        <link id="favicon" rel="icon" href="../i/.png"
        type="image/x-icon" /> <!-- small icon -->
        <link id="favicon" rel="icon" href="../i/.png"
        type="image/x-icon" /> <!-- speed dial -->
        <!-- viewport and sizing -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <!-- redirect -->
        <meta http-equiv="refresh" content="10; URL=https://linkitz.web.app" />
    </head>
    <body>
        <img src="../i/.png" style="display: none;">
    </body>
</html>
```