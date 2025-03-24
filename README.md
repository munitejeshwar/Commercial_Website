# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sports Hub</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Sports Hub(IPL)</h1>
        </header>
        <nav class="nav">
            <a href="#">Home</a>
            <a href="#">News</a>
            <a href="#">Teams</a>
            <a href="#">Matches</a>
            <a href="#">Contact</a>
        </nav>
        <div class="main-content">
            <section class="content">
                <h2>Latest Sports News</h2>
                <p>Stay updated with the latest sports events and scores.</p>
            </section>
            <aside class="sidebar">
                <h2>Upcoming Matches</h2>
                <ul>
                    <li>MI VS CSK - 5 PM</li>
                    <li>SRH VS RCB - 7 PM</li>
                    <li>KKR VS GG - 9 PM</li>
                </ul>
            </aside>
        </div>
        <footer class="footer">
            <p>&copy; 2025 Sports Hub. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>

```
## style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background-color: #eef2f3;
    color: #222;
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    max-width: 1200px;
    margin: 0 auto;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    overflow: hidden;
}

header {
    background: linear-gradient(135deg, #ff7b00, #ff3d00);
    color: white;
    text-align: center;
    padding: 2rem;
    font-size: 2rem;
    font-weight: bold;
}

.nav {
    display: flex;
    justify-content: center;
    background: #0a192f;
    padding: 1rem;
}

.nav a {
    color: #f1f1f1;
    text-decoration: none;
    font-weight: bold;
    margin: 0 15px;
    transition: 0.3s ease-in-out;
    font-size: 1.1rem;
}

.nav a:hover {
    text-decoration: underline;
    color: #ffcc00;
    transform: scale(1.1);
}

.main-content {
    display: flex;
    flex: 1;
    padding: 2rem;
    gap: 1.5rem;
}

.content {
    flex: 2;
    background: white;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.sidebar {
    flex: 1;
    background: #f9f9f9;
    padding: 1.5rem;
    border-left: 5px solid #ff3d00;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.sidebar h2 {
    margin-bottom: 1rem;
    color: #ff3d00;
}

.sidebar ul {
    list-style: none;
}

.sidebar ul li {
    padding: 10px;
    background: white;
    margin: 10px 0;
    border-radius: 5px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
}

.footer {
    background: #0a192f;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 1rem;
}

@media (max-width: 768px) {
    .main-content {
        flex-direction: column;
    }

    .nav {
        flex-wrap: wrap;
        justify-content: center;
    }
}

```
## OUTPUT
![image](https://github.com/user-attachments/assets/917410dc-63a1-4c6b-9c57-ba1946ce9322)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
