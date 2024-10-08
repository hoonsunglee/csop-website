<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>WELCOME TO EOP</title>
	<link rel="stylesheet" href="styles.css" />
	<script src="https://accounts.google.com/gsi/client" async defer></script>
	<style>
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
			background-color: #f4f4f4;
			color: #333;
		}
		header {
			background: #007bff;
			color: white;
			padding: 10px 0;
			text-align: center;
		}
		nav {
			margin: 20px 0;
		}
		nav a {
			margin: 0 15px;
			text-decoration: none;
			color: #007bff;
		}
		nav a:hover {
			text-decoration: underline;
		}
		.container {
			width: 80%;
			margin: auto;
			overflow: hidden;
		}
		.main-content {
			background: white;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
		}
		footer {
			text-align: center;
			padding: 10px 0;
			background: #007bff;
			color: white;
			position: relative;
			bottom: 0;
			width: 100%;
		}
	</style>
</head>
<body>
	<header>
		<h1>Welcome to EOP WEBSITE</h1>
	</header>

	<nav>
		<div class="container">
			<a href="#eop">Check EOP</a>
			<a href="#about">About</a>
			<a href="#profile">Profile</a>
		</div>
	</nav>

	<div class="container">
		<div
			id="g_id_onload"
			data-client_id="YOUR_GOOGLE_CLIENT_ID"
			data-callback="handleCredentialResponse"
			data-auto_prompt="false"
		></div>
		<div class="g_id_signin" data-type="standard"></div>

		<div class="main-content">
			<h2>About Us</h2>
			<p>
				Created by the CSOP club, this website records all your EOP violations and make regulating
				EOP more easier.
			</p>

			<h3>Our Services</h3>
			<p>
				We are involved in recording all EOP violations a student has gained and make the
				enforcement of EOP easier
			</p>

			<h3>Contact Us</h3>
			<p>
				If you have any questions, feel free to reach out via our <a href="#contact">contact page</a
				>.
			</p>
		</div>
	</div>

	<footer>
		<p>&copy; Created by the CSOP Club in 2024 All Rights Reserved.</p>
	</footer>
</body>
