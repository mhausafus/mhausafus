- 👋 Hi, I’m @mhausafus
- 👀 I’m interested in Cybersecurity...
- 🌱 I’m currently learning web development...
- 💞️ I’m looking to collaborate on social networking projects ...
- 📫 How to reach me -mhausafus@bethanywv.edu ... 

<!---
Author: Matthew Hausafus
Date: March 18, 2023
Project: My personal portfolio website
--->
<!DOCTYPE html>
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Portfolio</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<h1>Matthew Hausafus Portfolio</h1>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#skills">Skills</a></li>
				<li><a href="#projects">Projects</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	
	<main>
		<section id="about">
			<h2>About Me</h2>
			<p>Hello! My name is Matthew Hausafus and I am a Cybersecurity graduate of the class of 2022 at Bethany College in West Virginia.</p>
		</section>
		
		<section id="skills">
			<h2>Skills</h2>
			<ul>
				<li>Programming Language 1 - HTML</li>
				<li>Programming Language 2 - CSS</li>
				<li>Programming Language 3 - JavaScript</li>
				<li>Framework 1 - JQuery</li>
				<li>Framework 2 - Bootstrap</li>
				<li>Framework 3 - ASP.NET</li>
			</ul>
		</section>
		
		<section id="projects">
			<h2>Projects</h2>
			<ul>
				<li>Project 1 - Online Store</li>
				<li>Project 2 - Social Networking Website</li>
				<li>Project 3 - Educational Website</li>
				<li>Project 4 - Event Website</li>
				<li>Project 5 - Job Board</li>
				<li>Project 6 - User Admin Dashboard</li>
			</ul>
		</section>
		
		<section id="contact">
			<h2>Contact Me</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required><br>
				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required><br>
				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea><br>
				<input type="submit" value="Send">
			</form>
		</section>
	</main>
	
	<footer>
		<p>&copy; 2023 - Matthew Hausafus</p>
	</footer>

	<script src="script.js"></script>
</body>
</html>
