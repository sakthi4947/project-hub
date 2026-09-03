!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>To-Do List App</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>📝 To-Do List</h1>
    <form id="task-form">
      <input type="text" id="task-input" placeholder="Enter a task..." required>
      <input type="date" id="due-date-input">
      <button type="submit">Add Task</button>
    </form>
    <ul id="task-list"></ul>
  </div>
  <script src="script.js"></script>
</body>
</html>
