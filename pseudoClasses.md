# CSS3 Pseudo classes
Pseudo classes help match element based on the **state**, **structure**  or **position**. 


1. **:first-child** selects the first child of the parent element.
2. **:nth-child()** Takes an argument (2,3,4....even,odd) and selects that child element(s).
3. **:last-child** Selects the last child of the parent element
NOTE: The above pseudo classes are an example of **position** based.

<!-- Code Snippets -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pseudo Classes</title>
    <style>
        li:first-child {
            font-weight: bold;
        }

        li:nth-child(2){
            font-weight: bold;
        }

        li:last-child{
            font-weight: bold;
        }
    </style>
</head>
<body>
    <ol>
        <li>First</li>
        <li>Second</li>
        <li>Third</li>
    </ol>
</body>
</html>
