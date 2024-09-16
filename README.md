
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tengu42X</title>
    <style>
        body {
            font-family: 'Comic Sans MS', bold, sans-serif;
            background-color: #000000;
            color: #00ff00;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #00ff00;
            color: #000000;
            text-align: center;
            padding: 10px 0;
            font-size: 24px;
            font-family: monospace;
            white-space: pre;
        }
        nav {
            background-color: #003300;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: #00ff00;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        nav a:hover {
            background-color: #00cc00;
            color: #000000;
        }
        .container {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #00ff00;
            color: #000000;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        marquee {
            font-size: 18px;
            color: #00ff00;
        }
        .blinking-text {
            animation: blink 1s step-start infinite;
        }
        @keyframes blink {
            50% { opacity: 0; }
        }
    </style>
</head>
<body>
    <header>
 _____  _____  _   _  _____  _   _    ___  _____ __   __
|_   _||  ___|| \ | ||  __ \| | | |  /   |/ __  \\ \ / /
  | |  | |__  |  \| || |  \/| | | | / /| |`' / /' \ V / 
  | |  |  __| | . ` || | __ | | | |/ /_| |  / /   /   \ 
  | |  | |___ | |\  || |_\ \| |_| |\___  |./ /___/ /^\ \
  \_/  \____/ \_| \_/ \____/ \___/     |_/\_____/\/   \/
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>
    <marquee>Latest News: We're live!</marquee>
    <div class="container">
        <h1>Main Content</h1>
        <p>Welcome to Tengu42X, a retro-style website with a green and black theme!</p>
        <p class="blinking-text">This text is blinking!</p>
    </div>
    <footer>
        &copy; 2024 Tengu42X
    </footer>
</body>
</html>
