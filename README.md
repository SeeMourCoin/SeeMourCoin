#<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SeeMourCoin ($SMC) - Chaos Cat Meme Generator</title>
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
        .meme-container {
            margin-top: 20px;
        }
        .meme-img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 Welcome to SeeMourCoin ($SMC) 🚀</h1>
        <p>The **first** cryptocurrency powered by **chaos-driven next-gen cat memes**.</p>
        <p>Using advanced **chaos generation technology**, $SMC **revolutionizes** meme culture, one cat meme at a time.</p>
        
        <button class="chaos-button" onclick="generateMeme()">Generate a Chaos Meme</button>
        
        <div class="meme-container">
            <img id="memeImage" class="meme-img" src="https://cataas.com/cat/says/SeeMourCoin%20to%20the%20moon!" alt="Random Cat Meme">
        </div>
    </div>

    <script>
        function generateMeme() {
            // Using Cataas API for random cat memes
            document.getElementById("memeImage").src = "https://cataas.com/cat?" + new Date().getTime();
        }
    </script>
</body>
</html>