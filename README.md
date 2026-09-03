<!DOCTYPE html>
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

    <div class="filters">
      <button id="filter-all" class="filter-btn active">All</button>
      <button id="filter-completed" class="filter-btn">Completed</button>
      <button id="filter-pending" class="filter-btn">Pending</button>
    </div>

    <ul id="task-list"></ul>
  </div>
  <script src="script.js"></script>
</body>
</html>
