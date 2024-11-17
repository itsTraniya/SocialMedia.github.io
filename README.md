<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Story Game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Choose a Door</h1>
    <div class="doors">
        <div class="door" onclick="openDoor(1)">Door 1</div>
        <div class="door" onclick="openDoor(2)">Door 2</div>
        <div class="door" onclick="openDoor(3)">Door 3</div>
        <div class="door" onclick="openDoor(4)">Door 4</div>
    </div>
    <script src="script.js"></script>
</body>
</html>


body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f0f8ff;
}

h1 {
    margin-top: 50px;
}

.doors {
    display: flex;
    justify-content: center;
    margin-top: 50px;
    gap: 20px;
}

.door {
    width: 100px;
    height: 200px;
    background-color: #8b0000;
    color: white;
    font-size: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    border: 2px solid #000;
    border-radius: 10px;
}

.door:hover {
    background-color: #b22222;
}

function openDoor(doorNumber) {
    // Navigate to a different page for each door
    window.location.href = `door${doorNumber}.html`;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Door 1 Story</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to Door 1</h1>
    <p>This is where the story for Door 1 begins...</p>
    <a href="index.html">Go Back</a>
</body>
</html>
1
