## Type of css to write

```css
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        span {
            color: orange;
            background-color: aqua;
        }
    </style>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Inline CSS -->
    <div style="color: red; background-color: pink;">
        Inline CSS
    </div>

    <!-- Internal CSS -->
    <span>
        Internal CSS
    </span>

    <!-- External CSS -->
    <div>
        <span>
            <p>
                External CSS
            </p>
        </span>
    </div>

</body>

</html>


```