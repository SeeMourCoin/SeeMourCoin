<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SeeMourCoin ($SMC) - The Future of Cat Memes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #121212;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        h1 {
            color: #ffcc00;
        }
        .chaos-button {
            background-color: #ffcc00;
            border: none;
            padding: 15px 25px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
        }
        .chaos-button:hover {
            background-color: #ffaa00;
        }
        .meme-output {
            margin-top: 20px;
            font-size: 22px;
            font-style: italic;
            color: #ff99ff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 Welcome to SeeMourCoin ($SMC) 🚀</h1>
        <p>The **first** cryptocurrency powered by **chaos-driven next-gen cat memes**.</p>
        <p>Using advanced **chaos generation technology**, $SMC **revolutionizes** meme culture, one cat meme at a time.</p>
        
        <button class="chaos-button" onclick="generateMeme()">Generate a Chaos Meme</button>
        
        <p class="meme-output" id="memeText">😺 Click the button to unleash chaos! 😺</p>
    </div>

    <script>
        const memes = [
            "😹 When you accidentally send 10,000 $SMC to your cat...",
            "🐱‍👤 SMC: The only crypto endorsed by Schrödinger's cat.",
            "🚀 Cat memes + Blockchain = Financial Freedom",
            "💎 HODL, but make it cat memes!",
            "😼 Powered by chaos, ruled by felines!",
            "🐾 Every block mined, a new cat meme is born.",
            "🎩 This cat just made 10x on $SMC, what about you?"
        ];

        function generateMeme() {
            const randomMeme = memes[Math.floor(Math.random() * memes.length)];
            document.getElementById("memeText").innerText = randomMeme;
        }
    </script>
</body>
</html>