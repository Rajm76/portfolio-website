Simple Portfolio Website...

Welcome to my Simple Portfolio Website project! This is a basic web project built using HTML and CSS, designed to showcase a minimalist personal portfolio. It features three main pages: Home, About, and Contact. The Contact page includes a simple form with basic validation.

# Project Structure

Here's how the project is organized:

portfolio-website
    ├── index.html
    ├── about.html
    ├── contact.html
    ├── css
    │   └── styles.css
    └── images
        └── profile.jpg


# Setup Instructions

## 1. Clone the Repository
First, you'll need to clone the repository to your local machine

## 2. Open in Visual Studio Code
Next, open the project in Visual Studio Code:

1. *Launch VS Code*.
2.  Go to File > Open Folder and select the portfolio-website folder.

## 3. Live Preview with VS Code
To see your changes live, you can use the Live Server extension:

 *Open Live Server*:
   - Right-click on index.html in the Explorer pane and select Open with Live Server.
   - This will open your project in a new browser tab, letting you see your website live as you work on it.

### HTML Files

Here’s a quick look at the content of each HTML file:

#### index.html
The main page of the website, introducing the portfolio and linking to other pages.

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Simple Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Introduction</h2>
            <p>This is a simple portfolio website created with HTML and CSS.</p>
            <img src="images/profile.jpg" alt="Profile Picture">
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Simple Portfolio</p>
    </footer>
</body>
</html>


#### about.html
This page provides a brief background about the portfolio owner.

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Simple Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>About Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>My Background</h2>
            <p>Here is some information about me.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Simple Portfolio</p>
    </footer>
</body>
</html>


#### contact.html
A simple form that users can fill out to get in touch. It includes basic validation to ensure all fields are filled out correctly.

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Simple Portfolio</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <h1>Contact Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Get in Touch</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Simple Portfolio</p>
    </footer>
</body>
</html>


### CSS File

Here's the CSS that styles our website:

#### styles.css

css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 5px;
}

form input, form textarea {
    margin-bottom: 10px;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}


### Adding the Profile Image

Make sure to place your profile image (profile.jpg) in the images folder. Ensure the image name matches the reference in index.html.

### Form Validation

The form in contact.html uses HTML5 attributes (required and type="email") to ensure users fill out all fields correctly before submission.

### Conclusion

This project is a great starting point for creating a simple, clean personal portfolio website using HTML and CSS. It guides you through setting up the project, creating the HTML and CSS files, adding an image, and previewing the site using Live Server in Visual Studio Code.

### Future Enhancements

Here are a few ideas for future enhancements:
- Adding JavaScript for enhanced interactivity and form validation.
- Making the design responsive to ensure it looks good on all devices.
- Adding more pages or sections to showcase projects, skills, or a blog.

### License

This project is licensed under the MIT License - see the (LICENSE) file for details.

THANK YOU
