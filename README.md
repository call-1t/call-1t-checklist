<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Checklist</title>
  <style>
    body {
      font-family: "Inter", Arial, sans-serif;
      background: #f5f7fa;
      color: #222;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
    }
    h1 {
      margin-bottom: 30px;
      font-size: 2rem;
      color: #111;
    }
    .checklist {
      background: #fff;
      border-radius: 16px;
      padding: 25px 30px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      width: 100%;
      max-width: 600px;
    }
    .item {
      display: flex;
      align-items: flex-start;
      margin-bottom: 18px;
    }
    input[type="checkbox"] {
      margin-right: 12px;
      transform: scale(1.3);
      cursor: pointer;
    }
    label {
      flex: 1;
      line-height: 1.5;
    }
    .time {
      display: block;
      font-size: 0.85rem;
      color: #777;
      margin-top: 2px;
    }
  </style>
</head>
<body>
  <h1>My Checklist</h1>

  <div class="checklist" id="checklist">
    <div class="item">
      <input type="checkbox" id="learn-basics" />
      <label for="learn-basics">
        Learn basics of investing and trading
        <span class="time">~2–4 weeks</span>
      </label>
    </div>
    <div class="item">
      <input type="checkbox" id="open-demo" />
