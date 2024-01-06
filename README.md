
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body {
        text-align: center;
        background-color: #141414;
        font-family: Arial, sans-serif;
        color: #fff;
    }

    .buttons {
        padding: 8px 16px;
        margin: 17px 8px;
        font-size: 16px;
        border-radius: 100px 100px;
        cursor: pointer;
        background-color: #1b1b1b; 
        color: #fff;
        width: 300px;
        height: 50px;
        display: inline-flex;
        align-items: center;
        justify-content: center; /* Center the text horizontally */
        text-decoration: none;
        position: relative;
        transition: transform 0.3s;
    }

    .buttons:hover {
        transform: scale(1.2);
    }

    .buttons img {  
        width: 35px; 
        height: 35px;
        margin-right: 40px;
    }

    .buttons p {
        margin: 0;
        text-align: center; /* Center the text vertically */
        flex: 1;
        
    }
    
</style>
<body>
    <img src="data:image/jpeg;base64,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" alt = PhotoOfThem>
    <h2>@enderbenplayz</h2>
    <p style ="color:#b0b0b0">Subscribe to my YouTube and join the Discord!<br></p>
    
    <a href="https://youtube.com/@enderbenplayz"> <button class="buttons">
        <img src="https://static.vecteezy.com/system/resources/previews/018/930/572/non_2x/youtube-logo-youtube-icon-transparent-free-png.png" alt="YouTube Logo">
        <p>My Youtube</p>
    </button></a>

    <br>

    <a href="https://discord.gg/QZxEZABA4b"><button class="buttons">
        <img src="https://static.vecteezy.com/system/resources/previews/018/930/604/original/discord-logo-discord-icon-transparent-free-png.png" alt="Discord Logo">
        <p>My Discord</p>
    </button></a>

    <br>

    <a href="https://rec.net/user/enderbenplayz"><button class="buttons">
        <img src="https://cdn.rec.net/static/logos/face.png" alt="Rec.Net Logo">
        <p>My Rec.Net</p>
    </button></a>
</body>
</html>
