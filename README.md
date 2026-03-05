# VARK-Learning-PH
A personalized learning platform that highlights the different kinds of intelligences. 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>VARK Learning Hub</title>

<style>

:root{
--bg:#f4f8ff;
--text:#222;
--card:#ffffff;
--accent:#5a7cff;
}

body.dark{
--bg:#121212;
--text:#ffffff;
--card:#1e1e1e;
--accent:#ff7a7a;
}

body{
font-family:Arial, Helvetica, sans-serif;
background:var(--bg);
color:var(--text);
margin:0;
}

header{
background:linear-gradient(90deg,#5a7cff,#ff7a7a);
color:white;
padding:20px;
text-align:center;
}

nav{
display:flex;
justify-content:center;
gap:20px;
padding:15px;
background:var(--card);
box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

nav a{
text-decoration:none;
font-weight:bold;
color:var(--text);
}

.container{
padding:30px;
max-width:1100px;
margin:auto;
}

.section{
margin-bottom:50px;
}

.card{
background:var(--card);
padding:20px;
margin:15px 0;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card h3{
color:var(--accent);
}

button{
padding:10px 15px;
border:none;
border-radius:8px;
background:var(--accent);
color:white;
cursor:pointer;
}

footer{
text-align:center;
padding:20px;
background:var(--card);
}

</style>
</head>

<body>

<header>
<h1>🎓 VARK Learning Hub</h1>
<p>Innovative Learning Platform for Senior High School</p>

<button onclick="toggleMode()">🌙 Toggle Dark/Light Mode</button>
</header>

<nav>
<a href="#mil">Media & Information Literacy</a>
<a href="#arts">Contemporary Arts</a>
</nav>

<div class="container">

<section id="mil" class="section">

<h2>📱 Media and Information Literacy</h2>

<div class="card">
<h3>👁 Visual Learning</h3>

<p>PowerPoint and visual discussions about Media and Information Literacy.</p>

<ul>

<li>
<a href="https://sites.google.com/deped.gov.ph/mediainformationliteracy-sero/topic-1-introduction-to-media-and-information-literacy" target="_blank">
MIL Introduction Presentation
</a>
</li>

<li>
<a href="https://www.youtube.com/watch?v=Zqx5X6K4dFE" target="_blank">
Visual Discussion Video
</a>
</li>

<li>
<a href="https://ourworldindata.org/grapher/social-media-users" target="_blank">
Graph: Global Media Usage
</a>
</li>

</ul>

</div>

<div class="card">
<section id="visual">
    <h2>Visual Learning Style</h2>
    <div class="box">
        <h3>Media and Information Literacy</h3>
        <p>✔ PowerPoint Presentation on Types of Media</p>
        <p>✔ Charts showing Media Influence Statistics</p>
        <p>✔ Diagrams explaining Communication Process</p>
    </div>
    <div class="box">
        <h3>Contemporary Arts</h3>
        <p>✔ Slide Presentation of Art Movements</p>
        <p>✔ Visual Timeline of Philippine Contemporary Arts</p>
        <p>✔ Infographics of Art Elements and Principles</p>
    </div>
</section>
<h3>🎧 Auditory Learning</h3>

<p>Podcasts and audio discussions about media literacy.</p>

<ul>

<li>
<a href="https://open.spotify.com/show/3o3gkE" target="_blank">
Podcast: Media Literacy Today
</a>
</li>

<li>
<a href="https://www.youtube.com/watch?v=4_tvXmfJxvw" target="_blank">
Audio Lecture on Media Habits
</a>
</li>

</ul>

</div>

<div class="card">
<section id="auditory">
    <h2>Auditory Learning Style</h2>
    <div class="box">
        <h3>Media and Information Literacy</h3>
        <p>✔ Recorded lecture about Media Ethics</p>
        <p>✔ Podcast discussion on Fake News Awareness</p>
        <audio controls>
            <source src="audio-sample.mp3" type="audio/mpeg">
        </audio>
    </div>
    <div class="box">
        <h3>Contemporary Arts</h3>
        <p>✔ Verbal explanation of Art Movements</p>
        <p>✔ Group discussion on Meaning of Modern Art</p>
    </div>
</section>
<h3>📖 Reading & Writing</h3>

<ul>

<li>
<a href="https://helplineph.com/official-self-learning-modules/media-and-information-literacy/" target="_blank">
MIL Self Learning Modules
</a>
</li>

<li>
<a href="https://www.deped.gov.ph/wp-content/uploads/2019/01/SHS-Core_Media-and-Information-Literacy-CG.pdf" target="_blank">
MIL Curriculum Guide
</a>
</li>

<li>
<a href="https://writingcenter.unc.edu/tips-and-tools/media-literacy/" target="_blank">
Media Literacy Worksheets
</a>
</li>

</ul>

</div>

<div class="card">
<section id="reading">
    <h2>Reading & Writing Learning Style</h2>
    <div class="box">
        <h3>Media and Information Literacy</h3>
        <p>✔ Articles about Digital Literacy</p>
        <p>✔ Essay Writing on Media Responsibility</p>
        <p>✔ Research Paper on Information Disorder</p>
    </div>
    <div class="box">
        <h3>Contemporary Arts</h3>
        <p>✔ Reflection Paper on an Art Exhibit</p>
        <p>✔ Written Analysis of Artwork</p>
        <p>✔ Art Criticism Essay</p>
    </div>
</section>
<h3>🤝 Kinesthetic Learning</h3>

<p>Collaborative classroom activities.</p>

<ul>

<li>Group Activity: Analyze viral news and identify misinformation.</li>

<li>Role Play: Create a responsible media campaign.</li>

<li>Project: Produce a short educational podcast.</li>

</ul>

</div>

</section>

<section id="arts" class="section">
<section id="kinesthetic">
    <h2>Kinesthetic Learning Style</h2>
    <div class="box">
        <h3>Media and Information Literacy</h3>
        <p>✔ Create your own News Report Video</p>
        <p>✔ Role-playing Responsible Media User</p>
        <p>✔ Hands-on Fact Checking Activity</p>
    </div>
    <div class="box">
        <h3>Contemporary Arts</h3>
        <p>✔ Create a Mixed Media Artwork</p>
        <p>✔ Sculpture Making Activity</p>
        <p>✔ Performance Art Presentation</p>
        <button onclick="alert('Start your creative activity now!')">Start Activity</button>
    </div>
<h2>🎨 Contemporary Arts in the Philippines</h2>

<div class="card">

<h3>👁 Visual Learning</h3>

<ul>

<li>
<a href="https://www.nationalmuseum.gov.ph/" target="_blank">
Philippine Contemporary Art Gallery
</a>
</li>

<li>
<a href="https://artsandculture.google.com/project/philippine-art" target="_blank">
Visual Art Collections
</a>
</li>

<li>
<a href="https://www.youtube.com/watch?v=vY9J8s" target="_blank">
Contemporary Philippine Arts Video
</a>
</li>

</ul>

</div>

<div class="card">

<h3>🎧 Auditory Learning</h3>

<ul>

<li>
<a href="https://open.spotify.com/show/philippine-art-podcast" target="_blank">
Podcast: Philippine Contemporary Art
</a>
</li>

<li>
<a href="https://soundcloud.com/philippinearts" target="_blank">
Artist Interviews
</a>
</li>

</ul>

</div>

<div class="card">

<h3>📖 Reading & Writing</h3>

<ul>

<li>
<a href="https://lrmds.deped.gov.ph/detail/13261" target="_blank">
Contemporary Arts Module
</a>
</li>

<li>
<a href="https://www.culturalcenter.gov.ph/" target="_blank">
Philippine Arts Articles
</a>
</li>

<li>
<a href="https://www.teacherspayteachers.com/" target="_blank">
Art Worksheets
</a>
</li>

</ul>

</div>

<div class="card">

<h3>🤝 Kinesthetic Learning</h3>

<ul>

<li>Create a collaborative mural reflecting social issues.</li>

<li>Group performance using contemporary Filipino art forms.</li>

<li>Gallery walk critique activity.</li>

</ul>

</div>

</section>

</div>

<footer>

<p>VARK Learning Hub | Senior High School Learning Platform</p>

</footer>

<script>

function toggleMode(){
document.body.classList.toggle("dark");
}

</script>

</body>
</html>
