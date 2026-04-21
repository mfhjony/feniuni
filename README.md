# feniuni
feni unis
body
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The 101 Project</title>
<style>
body {
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
margin: 0;
line-height: 1.6;
color: #333;
}
        header {
background: #2c3e50;
color: white;
padding: 1rem 0;
text-align: center;
position: sticky;
top: 0;
}
        nav a {
color: white;
margin: 0 15px;
text-decoration: none;
font-weight: bold;
}
        .hero {
background: #ecf0f1;
padding: 60px 20px;
text-align: center;
}
        .container {
max-width: 1000px;
margin: auto;
padding: 20px;
}
        .grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 20px;
margin-top: 30px;
}
        .card {
border: 1px solid #ddd;
padding: 20px;
border-radius: 8px;
transition: transform 0.3s;
}
        .card:hover {
transform: translateY(-5px);
box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
        form {
display: flex;
flex-direction: column;
max-width: 500px;
margin: 30px auto;
}
        input, textarea, button {
margin-bottom: 15px;
padding: 10px;
border: 1px solid #ccc;
border-radius: 4px;
}
        button {
background: #27ae60;
color: white;
}
        footer {
background: #2c3e50;
color: white;
text-align: center;
padding: 20px 0;
margin-top: 40px;
}
    </style>
</head>
<body>
<header>
<h1>Code 101 Hub</h1>
<nav>
<a href="#home">Home</a>
<a href="#features">Features</a>
<a href="#contact">Contact</a>
</nav>
</header>
<section class="hero" id="home">
<h2>Clean, Semantic, and Responsive</h2>
<p>This page demonstrates the power of organized HTML and internal CSS.</p>
    </section>
<main class="container">
<section id="features">
<h2 style="text-align:center;">Core Principles</h2>
<div class="grid">
<div class="card">
