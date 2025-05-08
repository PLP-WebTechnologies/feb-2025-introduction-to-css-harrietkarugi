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
    <title>Glamour Cosmetics</title>
        <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f1f6;
            color: #444;
            box-sizing: border-box;
        }

        h1, h2 {
            color: #ff7ab1;
        }

        #header {
            background: linear-gradient(135deg, #ff6f91, #ff1c8f);
            color: white;
            text-align: center;
            padding: 40px 0;
            margin-bottom: 30px;
            border-bottom: 5px solid #fff;
        }

        #header h1 {
            font-size: 3em;
            font-weight: 600;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin: 0;
        }

        .text-content {
            background-color: white;
            padding: 30px;
            margin: 0 20px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .text-content h2 {
            font-size: 2em;
            font-weight: 600;
            margin-bottom: 15px;
        }

        .text-content p {
            font-size: 1.1em;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 12px;
            margin-top: 20px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
        }

        .button {
            background-color: #ff7ab1;
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            text-transform: uppercase;
            display: inline-block;
            transition: background-color 0.3s;
            margin-top: 30px;
            font-size: 1.1em;
        }

        .button:hover {
            background-color: #ff1c8f;
        }

        footer {
            text-align: center;
            padding: 30px;
            background-color: #ff1c8f;
            color: white;
        }

        footer p {
            margin: 0;
            font-size: 1.1em;
        }
    </style>
</head>
<body>

    <div id="header">
        <h1>Glamour Cosmetics</h1>
        <p>Where Beauty Meets Elegance</p>
    </div>

    <section class="text-content">
        <h2>Explore Our Latest Collection</h2>
        <p>Glamour Cosmetics is all about bringing out the best version of you. Our high-quality beauty products are crafted to highlight your natural beauty. From skincare essentials to stunning makeup products, we offer a wide range of items that suit every style and preference.</p>
        <p>Indulge yourself with our luxurious skincare range, designed to pamper your skin and give it that radiant glow. Our makeup collection includes vibrant colors, long-lasting formulas, and premium brushes that make application easy and flawless.</p>
        <p>Feel confident, beautiful, and glamorous with every product you try from our exclusive collection.</p>
    </section>

    <head>
<style>
img {
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 30px;
  width: 500px;
}
</style>
</head>
<body>

<h2>glamour cosmetic</h2>

<p>Use the border property to create glamour cosmetic:</p>

<img src="C:\Users\Admin\Downloads\images.jpg" alt="Glamour cosmetics" style="width:200px">

</body>
</html>
    <a href="#" class="button">Shop Now</a>

    <footer>
        <p>&copy; 2025 Glamour Cosmetics | All Rights Reserved</p>
    </footer>

</body>
</html>
