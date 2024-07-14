# Basic-ArtWork-Website
# Photo Blog

Welcome to the Photo Blog! This project showcases a simple, elegant photo gallery using HTML and CSS.

## Project Structure

The project consists of the following files:
- `photosite.html`: The main HTML file containing the structure and content of the photo blog.
- `photos.css`: The CSS file for styling the photo blog.

## Features

- **Responsive Design**: The gallery is designed to be responsive, with images arranged in a flexible layout.
- **Custom Fonts**: Utilizes the 'Raleway' font from Google Fonts for a clean and modern look.
- **Creative Commons Licensed Photos**: All photos are licensed under Creative Commons 2.0.

## File Details

### photosite.html

This file sets up the basic structure of the photo blog, including the navigation and photo gallery sections.

```html
<!DOCTYPE html>
<html>

<head>
    <title>Photo Blog</title>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="photos.css">
</head>

<body>
    <nav>Soban/Ahmad</nav>

    <section id="container">
        <!-- Photo credits and sources -->
        <img src="http://c1.staticflickr.com/9/8450/8026519634_f33f3724ea_b.jpg">
        <img src="http://c2.staticflickr.com/8/7218/7209301894_c99d3a33c2_h.jpg">
        <img src="http://c2.staticflickr.com/8/7231/6947093326_df216540ff_b.jpg">

        <img src="http://c1.staticflickr.com/9/8788/17367410309_78abb9e5b6_b.jpg">
        <img src="http://c2.staticflickr.com/6/5814/20700286354_762c19bd3b_b.jpg">
        <img src="http://c2.staticflickr.com/6/5647/21137202535_404bf25729_b.jpg">

        <img src="http://c2.staticflickr.com/6/5588/14991687545_5c8e1a2e86_b.jpg">
        <img src="http://c2.staticflickr.com/4/3888/14878097108_5997041006_b.jpg">
        <img src="http://c2.staticflickr.com/8/7579/15482110477_0b0e9e5421_b.jpg">
    </section>
    <footer>
        <p>All Photos Licensed Under Creative Commons 2.0</p>
        <a href="https://creativecommons.org/licenses/by/2.0/legalcode">Creative Commons License</a>
    </footer>
</body>

</html>
This file contains the styles for the photo blog, including layout and typography.
img {
    width: 30%;
    margin-bottom: 2%;
}

#container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    margin: 1% auto;
}

nav {
    font-family: 'Raleway', sans-serif;
    font-size: 1.5em;
    text-transform: uppercase;
    border-bottom: 2px solid #f1f1f1;
    width: 30%;
    margin: 0% 0% 0% 2.25%;
    padding: 1.2em 0;
}


Getting Started
To view the photo blog, simply open the photosite.html file in your web browser.

License
This project is licensed under the Creative Commons 2.0 License. See the LICENSE file for more details.

Credits
Photos by Massimo Margagnoni, Giuseppe Milo, and GörlitzPhotography.
Font: Raleway by Google Fonts.
Author
Soban Ahmad
Feel free to contribute to this project by forking the repository and creating pull requests. If you have any questions or suggestions, please open an issue.

Enjoy the Photo Blog!
