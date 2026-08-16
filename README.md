<!DOCTYPE html>
<html>
<head>
    <title>My Minecraft Fan Site</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="content">
        <h1>Welcome to Minecraft</h1>
        <p>Play the newest version of the world's best block game.</p>
        <a href="https://minecraft.net" target="_blank" class="btn">Get Latest Version</a>
    </div>
</body>
</html>
body {
    background-image: url('background.jpg');
    background-size: cover;
    font-family: Arial, sans-serif;
    color: white;
    text-align: center;
    padding-top: 100px;
}
.content {
    background-color: rgba(0, 0, 0, 0.7);
    display: inline-block;
    padding: 40px;
    border-radius: 10px;
}
.btn {
    background-color: #55ff55;
    color: black;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    display: inline-block;
    margin-top: 20px;
}
.btn:hover {
    background-color: #00aa00;
}
