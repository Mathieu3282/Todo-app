<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Todo App</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      margin-top: 50px;
    }

    .container {
      background: white;
      padding: 20px;
      border-radius: 10px;
      width: 300px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    h1 {
      text-align: center;
    }

    input {
      width: 70%;
      padding: 8px;
    }

    button {
      padding: 8px;
      cursor: pointer;
    }

    li {
      display: flex;
      justify-content: space-between;
      margin-top: 10px;
      padding: 5px;
      border-bottom: 1px solid #ddd;
    }

    .done {
      text-decoration: line-through;
      color: gray;
    }
