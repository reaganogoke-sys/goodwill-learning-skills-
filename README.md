# goodwill-learning-skills-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Goodwill Academy</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f3f4f6;
}

header{
    background:linear-gradient(90deg,#1d4ed8,#2563eb);
    color:white;
    padding:30px;
    text-align:center;
}

nav{
    background:#111827;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    margin:0 10px;
    text-decoration:none;
    font-weight:bold;
}

.container{
    max-width:1000px;
    margin:auto;
    padding:20px;
}

.card{
    background:white;
    padding:20px;
    border-radius:12px;
    margin-bottom:20px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

h2{
    color:#1d4ed8;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:10px;
}

.gallery div{
    background:#dbeafe;
    height:100px;
    border-radius:10px;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:12px;
}

input, textarea{
    width:100%;
    padding:10px;
    margin-top:8px;
    margin-bottom:12px;
    border:1px solid #ccc;
    border-radius:8px;
}

button{
    background:#1d4ed8;
    color:white;
    padding:10px 15px;
    border:none;
    border-radius:8px;
    cursor:pointer;
}

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:12px 15px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}

footer{
    text-align:center;
    padding:15px;
    background:#111827;
    color:white;
    margin-top:20px;
}
</style>

</head>

<body>

<header>
<h1>Goodwill Academy</h1>
<p>Excellence in Education & Character</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#mission">Mission</a>
<a href="#gallery">Gallery</a>
<a href="#admission">Admission</a>
</nav>

<div class="container">

<div class="card" id="about">
<h2>About Us</h2>
<p>Goodwill Academy is committed to raising intelligent, disciplined and responsible students through quality education and modern teaching methods.</p>
</div>

<div class="card" id="mission">
<h2>Our Mission</h2>
<p>To develop future leaders through academic excellence, discipline, and innovation.</p>
</div>

<div class="card" id="gallery">
<h2>School Gallery</h2>
<div class="gallery">
<div>Classroom</div>
<div>Students</div>
<div>Teachers</div>
<div>Lab</div>
<div>Library</div>
<div>Events</div>
</div>
</div>

<div class="card" id="admission">
<h2>Admission Form</h2>
<form>
<label>Full Name</label>
<input type="text" placeholder="Enter student name">

<label>Class Applying For</label>
<input type="text" placeholder="e.g. JSS1, SS2">

<label>Parent Contact</label>
<input type="text" placeholder="Phone number">

<label>Message</label>
<textarea rows="4" placeholder="Any message..."></textarea>

<button type="button">Submit Application</button>
</form>
</div>

</div>

<a class="whatsapp" href="https://wa.me/234" target="_blank">
Chat Us 💬
</a>

<footer>
© 2026 Goodwill Academy | THE FUTURE IS ME 
</footer>

</body>
</html>