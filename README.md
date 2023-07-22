<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyberpunk README</title>
    <style>
        body {
            background-color: #000;
            color: #0F0;
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 50px;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 30px;
            text-transform: uppercase;
            letter-spacing: 5px;
        }

        .blink {
            animation: blink-animation 1s steps(5, start) infinite;
            -webkit-animation: blink-animation 1s steps(5, start) infinite;
        }

        @keyframes blink-animation {
            to {
                visibility: hidden;
            }
        }

        @-webkit-keyframes blink-animation {
            to {
                visibility: hidden;
            }
        }

        .rainbow-text {
            background-image: linear-gradient(45deg, #f06, #0f6, #06f, #60f, #f06);
            background-size: 400% 100%;
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            animation: rainbow-animation 2s linear infinite;
            -webkit-animation: rainbow-animation 2s linear infinite;
        }

        @keyframes rainbow-animation {
            0% {
                background-position: 0% 50%;
            }
            100% {
                background-position: 400% 50%;
            }
        }

        @-webkit-keyframes rainbow-animation {
            0% {
                background-position: 0% 50%;
            }
            100% {
                background-position: 400% 50%;
            }
        }
    </style>
</head>
<body>
    <h1 class="rainbow-text">Cyberpunk README <span class="blink">_</span></h1>
    <p>Welcome to my cyberpunk-inspired project! Feel the neon energy as you dive into the dark alleys of futuristic coding.</p>
    <p>Here you'll find:</p>
    <ul>
        <li>An immersive cyberpunk theme with neon colors and dark vibes.</li>
        <li>Fast-paced animations that will make your head spin!</li>
        <li>State-of-the-art technology, breaking the boundaries of what you thought was possible.</li>
        <li>Wicked cool features that will make you question reality.</li>
    </ul>
    <p>So put on your virtual reality headset, and let's embark on this epic cyber journey together.</p>
    <p>Stay connected in cyberspace<span class="blink">_</span></p>
</body>
</html>

