Assignment 4.5 — Multi-Page College Club Website
Here is a complete, multi-page solution for your college club website. This project includes all four required pages (index.html, about.html, registration.html, and contact.html), consistent navigation, an events schedule table, metadata, and favicons.

To keep everything organized, create a project folder with a css folder (for your stylesheet) and an images folder (for your favicon and photos).

1. Global CSS (css/style.css)
Save this file inside a css folder so all four pages share a clean, consistent look.

CSS
/* Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f9;
}

/* Header & Navigation */
header {
    background: #1a252f;
    color: #fff;
    padding: 1.5rem 0;
    text-align: center;
}

nav {
    background: #2c3e50;
    padding: 0.8rem;
    text-align: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    font-size: 1.1rem;
}

nav a:hover, nav a.active {
    color: #1abc9c;
    text-decoration: underline;
}

/* Main Content Layout */
main {
    max-width: 900px;
    margin: 2rem auto;
    background: #fff;
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

h1, h2 {
    color: #2c3e50;
    margin-bottom: 1rem;
}

p {
    margin-bottom: 1rem;
}

/* Tables */
table {
    width: 100%;
    border-collapse: collapse;
    margin: 1.5rem 0;
}

th, td {
    padding: 12px;
    border: 1px solid #ddd;
    text-align: left;
}

th {
    background-color: #2c3e50;
    color: white;
}

tr:nth-child(even) {
    background-color: #f9f9f9;
}

/* Forms */
form label {
    display: block;
    margin-top: 1rem;
    font-weight: bold;
}

form input, form select, form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    margin-top: 1.5rem;
    background: #1abc9c;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1rem;
    font-weight: bold;
}

form button:hover {
    background: #16a085;
}

/* Footer */
footer {
    text-align: center;
    padding: 1.5rem;
    background: #1a252f;
    color: white;
    margin-top: 2rem;
}