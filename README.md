# Game-Tic-tac-toe
This is a game Tic-tac-toe
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Tic-Tac-Toe 2 Pemain</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #84fab0, #8fd3f4);
      overflow: hidden;
    }

    h1 {
      color: #333;
      margin-bottom: 10px;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
    }

    .board {
      display: grid;
      grid-template-columns: repeat(3, 100px);
      gap: 10px;
      margin: 20px;
      background-color: rgba(255,255,255,0.1);
      padding: 10px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    .cell {
      width: 100px;
      height: 100px;
      background: white;
      border-radius: 10px;
      display: flex;
