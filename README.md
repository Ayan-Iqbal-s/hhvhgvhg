<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffC0CB;
            text-align: center;
            padding: 50px;
        }
        .proposal-container {
            display: none;
            margin-top: 20px;
            border: 2px solid #add8e6;
            padding: 20px;
            background-color: #ff69B4;
            border-radius: 10px;
            width: 300px;
            margin: 0 auto;
        }
        .buttons {
            margin-top: 20px;
        
        }
        button {
            padding: 10px 20px;
            background-color: #ff1493;
            margin: 5px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes-btn {
            background-color: #32cd32;
            color: #ffffff;
        }
        .no-btn {
            background-color: #ff4500;
            color: #ffffff;
        }
    </style>
</head>
<body>
    <h1>Hello [ Seeba ]!</h1>
    <p>I have something special to ask you...</p>
    <button id="revealProposal">Open the Message</button>

    <div id="proposal" class="proposal-container">
        <h2>My Proposal</h2>
        <p>Dear [ Seeba ],</p>
        <p>
            From the moment we met, I knew you were someone special. Your smile, your laughter, and your kindness have captured my heart. I cherish every moment we spend together and can't imagine my life without you.
        </p>
        <p>
            Would you do me the honor of being my mine? I promise to always support you, make you smile, and be there for you through thick and thin.
        </p>
        <p>With all my love,</p>
        <p>[Yours]</p>

        <div class="buttons">
            <button class="yes-btn" onclick="respond('yes')">Yes</button>
            <button class="no-btn" onclick="respond('no')">No</button>
        </div>
    </div>

    <script>
        document.getElementById("revealProposal").onclick = function() {
            document.getElementById("proposal").style.display = "block";
        };

        function respond(answer) {
            if (answer === 'yes') {
                alert("Yay! I'm so happy you said yes!");
            } else {
                alert("That's okay. I'm glad I could share my feelings with you.");
            }
        }
    </script>
</body>
</html>
