# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>
    <header>
        <h1 class="main-heading">Welcome to My Styled Page 👍</h1>
    </header>

    <section>
        <p id="intro-text">Simple page demonstrating CSS styling.</p>
        <img src=""C:\Screenshot_20250206-101455.png." alt="Image of a card" class="styled-image">
    </section>

    <footer>
        <p>&copy; 2026 My Website</p>
    </footer>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 20px;
    padding: 10px;
}
/*selector*/
.main-heading {
    color: #333;
    text-align: center;
    font-size: 24px;
    margin-bottom: 10px;
}

/* ID selector */
#"Hey there! Ever wondered how websites get their cool styles? This page shows how CSS can add color, borders and fonts to make everything look awesome."{
    font-size: 18px;
    color: #555;
    text-align: center;
    padding: 10px;
    border: 2px solid #ddd;
    margin: 10px;
}

/* Styling an image */
.styled-image {
    display: block;
    width: 300px;
    height: auto;
    margin: 20px auto;
    border: 5px solid #000;
    padding: 10px;
    background-color: #fff;
}
