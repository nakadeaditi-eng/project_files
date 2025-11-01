<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Aditi Nakade Portfolio</title>
<style>
/* ===== BASIC RESET ===== */
* {margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif;}
body {background:#0a0a0a; color:#fff; min-height:100vh;}

/* ===== HEADER ===== */
header {text-align:center; padding:60px 20px 20px;}
header h1 {font-size:3rem; color:#ffd700; letter-spacing:2px; text-shadow: 0 0 10px #ffd700;}
nav {display:flex; justify-content:center; gap:25px; margin-top:20px;}
nav a {color:#fff; text-decoration:none; font-weight:500; transition:0.3s;}
nav a:hover {color:#ffd700; text-shadow:0 0 8px #ffd700;}

/* ===== SECTIONS ===== */
section {max-width:1100px; margin:60px auto; background:rgba(30,30,30,0.9); border-radius:20px; padding:40px; box-shadow:0 10px 25px rgba(0,0,0,0.3);}
h2 {text-align:center; color:#ffd700; margin-bottom:25px; font-size:2rem;}
p {text-align:center; line-height:1.8;}

/* ===== SKILLS ===== */
.skills {display:flex; flex-wrap:wrap; justify-content:center; gap:15px; margin-top:20px;}
.skill {background:#444; padding:10px 25px; border-radius:30px; font-weight:500; color:#ffd700; transition: transform 0.3s;}
.skill:hover {transform: scale(1.1);}

/* ===== PROJECTS ===== */
.projects {display:grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap:20px; margin-top:30px;}
.card {background:#1c1c1c; border-radius:20px; padding:20px; text-align:center; transition:all 0.3s; box-shadow:0 4px 15px rgba(0,0,0,0.5);}
.card h3 {color:#ffd700; margin-bottom:10px;}
.card p {color:#ccc; font-size:0.95rem;}
.card:hover {transform: translateY(-8px); box-shadow:0 8px 25px rgba(255,215,0,0.4);}
.card a {display:inline-block; margin-top:10px; padding:8px 15px; border-radius:20px; background:#ffd700; color:#0a0a0a; text-decoration:none; font-weight:500; transition:0.3s;}
.card a:hover {background:#e6c200;}

/* ===== FOOTER ===== */
footer {text-align:center; padding:20px; color:#ffd700; background:#111; margin-top:40px; border-top:1px solid #333;}
footer a {color:#ffd700; text-decoration:none; font-weight:600;}
footer a:hover {text-decoration:underline;}

/* ===== RESPONSIVE ===== */
@media(max-width:600px){header h1{font-size:2.2rem;} nav{flex-direction:column; gap:15px;}}
</style>
</head>
<body>

<header>
  <h1>Aditi Nakade</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <p>Hello! I'm <b>Aditi Nakade</b>, a creative engineering student passionate about building beautiful, functional projects. I love coding, design, and exploring new technologies to create unique solutions.</p>
</section>

<section id="skills">
  <h2>My Skills</h2>
  <div class="skills">
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
     <div class="skill">Projects</div>
   
  </div>
</section>

<section id="projects">
  <h2>HTML</h2>
  <div class="projects">
    
     
    <div class="card">
      <h3>Project 1</h3>
      <a href="./Admission submited.html" target="_blank">View Project</a>
    </div>
    <div class="card">
      <h3>Project 2</h3>
      <p>Short description of project 2.</p>
      <a href="./Admission-form - Personal details.html" target="_blank">View Project</a>
    </div>
    <div class="card">
      <h3>Project 3</h3>
      <p>Short description of project 3.</p>
      <a href="./College-Admission-Form - Academic and Course Details.html" target="_blank">View Project</a>
    </div>
    <div class="card">
        <h3>Project 4</h3>
        <p>Short description of project 4.</p>
        <a href="./College-Admission-Form - Contact Details.html" target="_blank">View Project</a>
    </div>
    <div class="card">
        <h3>Project 5</h3>
        <p>Short description of project 5.</p>
        <a href="./background-image (2).html" target="_blank">View Project</a>
        </div>
    <div class="card">
        <h3>Project 6</h3>
        <p>Short description of project 6.</p>
        <a href="./Nakade/class-one.html" target="_blank">View Project</a>
        </div>
    <div class="card">
        <h3>Project 7</h3>
        <p>Short description of project 7.</p>
        <a href="./background-image.html" target="_blank">View Project</a>
        </div>
    <div class="card">
        <h3>Project 8</h3>
        <p>Short description of project 8.</p>
        <a href="./chess-.html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 9</h3>
        <p>Short description of project 9.</p>
        <a href="./Nakade/Media -Query-layout.html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 10</h3>
        <p>Short description of project 10.</p>
        <a href="./display-properties example.html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 11</h3>
        <p>Short description of project 11.</p>
        <a href="./Nakade/Grid-layout.html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 12</h3>
        <p>Short description of project 12.</p>
        <a href="./Nakade/Grid-layout(2).html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 13</h3>
        <p>Short description of project 13.</p>
        <a href="./Nakade/nav-bar.html" target="_blank">View Project</a>
        </div>
        <div class="card">
        <h3>Project 14</h3> 
        <p>Short description of project 14.</p>
        <a href="./Nakade/product-card.html" target="_blank">View Project</a>
        </div>
        <div class="card">
            <h3>Project 15</h3>
            <p>Short description of project 15.</p>
            <a href="./div-Tag-one(2).html" target="_blank">View Project</a>
        </div>
        <div class="card">
            <h3>Project 16</h3>
            <p>Short description of project 16.</p>
            <a href="./div-Tag-one(1) (1).html" target="_blank">View Project</a>
            </div>
        <div class="card">
            <h3>Project 17</h3>
            <p>Short description of project 17.</p>
            <a href="./form.html" target="_blank">View Project</a>
            </div>
        <div class="card">
            <h3>Project 18</h3>
            <p>Short description of project 18.</p>
            <a href="./division-layout(1).html" target="_blank">View Project</a>
            </div>
        <div class="card">
            <h3>Project 19</h3> 
            <p>Short description of project 19.</p>
            <a href="./division-layout(2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 20</h3> 
            <p>Short description of project 20.</p>
            <a href="./Div-tag-one-one.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 21</h3> 
            <p>Short description of project 21.</p>
            <a href="./div-Tag-one.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 22</h3> 
            <p>Short description of project 22.</p>
            <a href="./div-Tag-one(2)(2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 23</h3> 
            <p>Short description of project 23.</p>
            <a href="./division-layout(4).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 24</h3> 
            <p>Short description of project 24.</p>
            <a href="./formtag (1).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 25</h3> 
            <p>Short description of project 25.</p>
            <a href="./assets (1).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 26</h3> 
            <p>Short description of project 26.</p>
            <a href="./formtag.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 27</h3> 
            <p>Short description of project 27.</p>
            <a href="./login.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 28</h3> 
            <p>Short description of project 28.</p>
            <a href="./NAme of blocks.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 29</h3> 
            <p>Short description of project 29.</p>
            <a href="./signup.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 30</h3> 
            <p>Short description of project 30.</p>
            <a href="./index.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 31</h3> 
            <p>Short description of project 31.</p>
            <a href="./Nakade/Media-Query-layout(2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 32</h3> 
            <p>Short description of project 32.</p>
            <a href="./Nakade/Grid-layout(2).html" target="_blank">View Project</a>
            </div>
           
            <div class="card">
            <h3>Project 33</h3> 
            <p>Short description of project 34.</p>
            <a href="./table-with-internal-css.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 34</h3> 
            <p>Short description of project 35.</p>
            <a href="./Table-tag (2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 35</h3> 
            <p>Short description of project 36.</p>
            <a href="./Type-selector-two.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 36</h3> 
            <p>Short description of project 36.</p>
            <a href="./Nakade/division-layout-four.html" target="_blank">View Project</a>
            </div>
            
             <div class="card">
            <h3>Project 37</h3> 
            <p>Short description of project 37.</p>
            <a href="./Type-selector.html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 38</h3> 
            <p>Short description of project 37.</p>
            <a href="./Admission-form(2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
            <h3>Project 39</h3> 
            <p>Short description of project 37.</p>
            <a href="./map.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 40</h3> 
            <p>Short description of project 37.</p>
            <a href="./Nakade/chessboard-with-grid.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 41</h3> 
            <p>Short description of project 37.</p>
            <a href="./Nakade/new-file.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 42</h3> 
            <p>Short description of project 37.</p>
            <a href="./nav.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 43</h3> 
            <p>Short description of project 37.</p>
            <a href="./programming-basics.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 44</h3> 
            <p>Short description of project 37.</p>
            <a href="./table-with-internal-css.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 45</h3> 
            <p>Short description of project 37.</p>
            <a href="./Table-tag (2).html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 46</h3> 
            <p>Short description of project 37.</p>
            <a href="./universal-calendar.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 47</h3> 
            <p>Short description of project 37.</p>
            <a href="./My-portfolio.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 48</h3> 
            <p>Short description of project 37.</p>
            <a href="./Nakade/Aditi-portfolio.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 49</h3> 
            <p>Short description of project 37.</p>
            <a href="./messenger.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 50</h3> 
            <p>Short description of project 37.</p>
            <a href="./Type-selector.html" target="_blank">View Project</a>
            </div>
            <div class="card">
             <h3>Project 51</h3> 
            <p>Short description of project 37.</p>
            <a href="./Type-selector-two.html" target="_blank">View Project</a>
            </div>
            <div class="card">
      <h3>Project 52</h3>
      <a href="./Nakade/calculator.html" target="_blank">View Project</a>
    </div>


  </div>
 
</section>
<section id="projects">
  <h2>All projects</h2>
  <div class="projects">
    
    <div class="card">
      <h3>All projects</h3>
      <a href="./Nakade/calculator.html" target="_blank">View Project</a>
    </div>
 <div class="card">
      <h3>All projects</h3>
      <a href="./Nakade/chessboard-with-grid.html" target="_blank">View Project</a>
    </div>
     <div class="card">
      <h3>All projects</h3>
      <a href="./Nakade/product-card.html" target="_blank">View Project</a>
    </div>
     <div class="card">
      <h3>All projects</h3>
      <a href="./Admission-form - Personal details.html" target="_blank">View Project</a>
    </div>
 <div class="card">
      <h3>All projects</h3>
      <a href="./College-Admission-Form - Academic and Course Details.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./College-Admission-Form - Contact Details.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Admission submited.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./chess-board-styling css.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./display-properties example.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./login.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./signup.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./table-with-internal-css.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./formtag (1).html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Type-selector.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Admission-form(2).html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Table-tag (2).html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./form.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./index.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Type-selector-two.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./messenger.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Nakade/Aditi-portfolio.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./My-portfolio.html">View Project</a>
</div>
<div class="card">
<h3>All projects</h3>
      <a href="./universal-calendar.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./programming-basics.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./nav.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./Nakade/new-file.html">View Project</a>
</div>
<div class="card">
      <h3>All projects</h3>
      <a href="./map.html">View Project</a>
</div>
  </div>
</section>

<section id="contact">
  <h2>Contact Me</h2>
  <p>📧 <b>Email:</b> <a href="mailto:nakadeaditi@gmail.com">nakadeaditi@gmail.com</a></p>
  <p>📞Mobile number: +91 9168225231</p>
</section>

</body>
</html>

