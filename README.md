# bala07.github.io
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bala B | Cloud Engineer Portfolio</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#0f172a;
color:white;
line-height:1.6;
}

header{
background:#1e293b;
padding:20px;
position:sticky;
top:0;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
max-width:1100px;
margin:auto;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
}

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.hero h1{
font-size:3rem;
color:#38bdf8;
}

.hero p{
font-size:1.2rem;
max-width:700px;
margin:20px 0;
}

.btn{
background:#38bdf8;
color:#000;
padding:12px 25px;
border-radius:5px;
text-decoration:none;
font-weight:bold;
}

section{
padding:60px 20px;
max-width:1100px;
margin:auto;
}

.section-title{
text-align:center;
font-size:2rem;
margin-bottom:30px;
color:#38bdf8;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:20px;
border-radius:10px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

footer{
text-align:center;
padding:20px;
background:#1e293b;
}
</style>
</head>

<body>

<header>
<nav>
<h2>Bala B</h2>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section class="hero">
<h1>Bala B</h1>
<h2>Aspiring Cloud Engineer</h2>

<p>
B.Tech Information Technology student passionate about
Cloud Computing, Linux, Networking and DevOps.
Building practical cloud solutions using Google Cloud Platform.
</p>

<a href="#projects" class="btn">View Projects</a>
</section>

<section id="about">
<h2 class="section-title">About Me</h2>

<div class="card">
<p>
I am a B.Tech IT student from Chennai with strong interest
in Cloud Engineering, Linux Administration and DevOps.
Currently learning Google Cloud Platform and building
hands-on projects to prepare for Cloud Engineering roles.
</p>
</div>
</section>

<section id="skills">
<h2 class="section-title">Skills</h2>

<div class="skills">

<div class="card">
<h3>Cloud</h3>
<p>Google Cloud Platform, AWS Fundamentals</p>
</div>

<div class="card">
<h3>Linux</h3>
<p>Ubuntu, Cloud Shell</p>
</div>

<div class="card">
<h3>Networking</h3>
<p>TCP/IP, DNS, DHCP, VPC, NAT, Subnetting</p>
</div>

<div class="card">
<h3>Programming</h3>
<p>Python, Java, C</p>
</div>

<div class="card">
<h3>DevOps</h3>
<p>Git, GitHub, Docker</p>
</div>

<div class="card">
<h3>Database</h3>
<p>MySQL</p>
</div>

</div>
</section>

<section id="projects">
<h2 class="section-title">Projects</h2>

<div class="projects">

<div class="card">
<h3>Cloud VM Deployment</h3>
<p>
Created and managed Virtual Machines using
Google Compute Engine and configured firewall rules.
</p>
</div>

<div class="card">
<h3>VPC Network Setup</h3>
<p>
Designed VPC networks, configured Cloud NAT
and enabled Private Google Access.
</p>
</div>

<div class="card">
<h3>Static Website Hosting</h3>
<p>
Hosted static websites using Cloud Storage
with scalable cloud architecture.
</p>
</div>

</div>
</section>

<section id="contact">
<h2 class="section-title">Contact</h2>

<div class="card">
<p>Email: balabaskar1107@gmail.com</p>
<p>Phone: +91 9042431479</p>

<br>

<a class="btn" href="https://github.com/" target="_blank">
GitHub
</a>

<a class="btn" href="https://linkedin.com/" target="_blank">
LinkedIn
</a>

</div>
</section>

<footer>
<p>© 2026 Bala B | Cloud Engineer Portfolio ☁️</p>
</footer>

</body>
</html>
