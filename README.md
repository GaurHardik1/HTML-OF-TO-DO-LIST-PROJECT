# HTML-OF-TO-DO-LIST-PROJECT
BEST PROJECT FOR BEGINEER

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="favicon" type="image/x-icon" href= "favicon (2).png">
</head>
<body>
    <div class="container">
        <div class="todo-app">
            <h2>TO DO LIST</h2>
            <div class="row">
            <input type="text" id="input" placeholder="Enter your task">
            <button onclick="addTask()">Add</button>
        </div>
            <ul id="list-container">
                <!-- <li class="checked">Task 1</li>
                <li>Task 2</li>
                <li>Task 3</li> -->
            </ul>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
