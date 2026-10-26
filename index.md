Step 1: Create index.html (Home Page)
Create your first file named index.html and paste the following code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Website</title>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> | 
        <a href="about.html">About</a> | 
        <a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub (External)</a>
    </nav>

    <hr>

    <!-- Header & Introduction -->
    <header>
        <h1>Welcome to My Website</h1>
        <p>Hello! This is the home page of my simple two-page website built for Assignment 3.1.</p>
    </header>

    <main>
        <h2>Explore More</h2>
        <p>Use the navigation links above to learn more about this project on the About page or visit an external site securely.</p>
    </main>

</body>
</html>
Step 2: Create about.html (About Page)
Create a second file in the same folder named about.html and paste the following code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - My Website</title>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="index.html">Home</a> | 
        <a href="about.html">About</a> | 
        <a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub (External)</a>
    </nav>

    <hr>

    <!-- About Content -->
    <main>
        <h1>About This Website</h1>
        <p>This page is part of Assignment 3.1, demonstrating how to link multiple HTML pages together using relative paths and how to safely link to external websites using target attributes.</p>
    </main>

</body>
</html>
Key Requirements Checklist Met:
Two Pages: Both index.html and about.html are created.

Navigation Bar & Links: Both pages feature a consistent navigation bar allowing seamless switching back and forth using relative paths (href="index.html" and href="about.html").

External Link: Includes an external link to GitHub.

Security & New Tab: The external link uses target="_blank" to open in a new tab and rel="noopener noreferrer" for enhanced security.

Submission Requirements
HTML Files: Submit both your index.html and about.html files.

Screenshot: Take a screenshot of your working website in your browser (showing the navigation bar and open pages) and submit it alongside your files!