# Ex.08 Design of Interactive Image Gallery
## Date:

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
INDEX.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main id="gallery">
        <div class="gallery-container">
            <img src="image1.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
            <img src="image3.png" alt="Image 3">
            <img src="image4.webp" alt="Image 4">
            <img src="image5.jpg" alt="Image 5">
            <img src="image6.jpg" alt="Image 6">
            <img src="image7.jpeg" alt="Image 7">
            <img src="image8.jpg" alt="Image 8">
            <img src="image9.jpg" alt="Image 9">
            <img src="image10.png" alt="Image 10">
            <img src="image11.jpg" alt="Image 11">
            <img src="image12.webp" alt="Image 12">
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Your Website</p>
    </footer>
</body>
</html>
```
STYLE.CSS
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.gallery-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 10px;
    padding: 20px;
}

.gallery-container img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #f1f1f1;
    margin-top: 20px;
}
```
## OUTPUT:
![384788436-a4c6c5da-e713-43b8-b951-7a289cf7d371](https://github.com/user-attachments/assets/ba26c6b2-66e0-4bbc-b53e-3b05a3bf0bbe)

![384788609-dfbb3ece-5a00-4842-986e-85dd196b230f](https://github.com/user-attachments/assets/47db0cdb-968f-412a-95c7-b8356173ac6b)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
