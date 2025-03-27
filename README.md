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
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>W3_assegnment</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>THIS IS MY ASSEGNMENT FOR THE WEAK 3</h1>
    <p class="bg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus neque 
        quaerat aliquam modi error quasi qui labore? Error id quo laborum. Quod voluptate
         facere natus omnis eos, nostrum suscipit nulla.</p>
    <div><img src="3.jpg" alt="image"  class="benja">
        <img src="pc1.jpg" alt="image 2"  class="benja">
    </div>
    <h3 id="weak1">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Non, repudiandae. Rem
         consectetur, asperiores, pariatur necessitatibus aliquid ratione 
        reiciendis veritatis architecto, eligendi facere placeat fuga nihil labore eum. Unde, debitis sunt!</h3>
    
</body>
</html>




body{
    background-color: rgb(201, 239, 239);
    margin: 20px ;
}
h1{
    text-align: center;
    background-color: blue;
}

.bg{
    text-align: center;
    -ms-text-size-adjust: auto;
    font-size: medium;
    font-family: sans-serif;
}

img {
    width: 500px;
    height: 400px;
    object-fit: cover;  
    
}

div{
    text-align: center;
    padding: auto;
}

.benja{
    border-radius: 10px;
}
#weak1 {
    color: rgb(192, 189, 134);
    font-size: 20px;
    font-family: sans-serif;
}


