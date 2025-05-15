<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>DevLaunch: From Learning to Liftoff</title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
  }
  .header {
    padding: 60px 20px;
   
    background: linear-gradient(135deg, #8B0000, #A52A2A);
    text-align: center;
    color: white;
  }
  .header h1 {
    font-size: 2.5em;
    margin-bottom: 8px;
  }
  .header p {
    font-size: 1em;
  }
  .navbar {
    display: flex;
    justify-content: center;
    background-color: #333;
    flex-wrap: wrap;
  }
  .navbar a {
    padding: 14px 20px;
    color: white;
    text-decoration: none;
  }
  .navbar a:hover {
    background-color: #ddd;
    color: black;
  }
  .content {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 15px;
  }
  h2 {
    color: #8B0000; 
    margin-bottom: 10px;
    border-bottom: 2px solid #8B0000;
    padding-bottom: 8px;
  }
  p {
    margin-bottom: 15px;
  }
  table {
    width: 100%;
    border-collapse: collapse;
    background: #fff;
    margin-bottom: 40px;
  }
  caption {
    font-size: 1.3em;
    margin-bottom: 8px;
    font-weight: bold;
  }
  th, td {
    border: 1px solid #ccc;
    padding: 10px;
  }
  th {
    background-color: #8B0000; 
    color: white;
  }
  @media(max-width: 768px) {
    h1 {
      font-size: 2em;
    }
    .navbar {
      flex-direction: column;
    }
    .navbar a {
      width: 100%;
      text-align: center;
      padding: 12px 0;
    }
  }
</style>
</head>
<body>
<header class="header">
  <h1>DevLaunch: From Learning to Liftoff</h1>
  <p>BY: Shuaib Mohamed</p>
</header>
<nav class="navbar">
  <a href="DEv5.html" target="_blank" aria-label="About me">About me</a>
</nav>
<div class="content">
  <section>
    <h2>About Me</h2>
    <p>This is my first web design project in high school. I will share what I learned this year.</p>
  </section>
  <section>
    <h2>What I Learned</h2>
    <pre style="background:#f4f4f4; padding:10px; border-radius:8px;">
- Basic HTML
- CSS styling
- Creating tables
- Using images
- Web accessibility
    </pre>
  </section>
  <section>
    <h2>My Schedule</h2>
    <table>
      <caption>My Info</caption>
      <thead>
        <tr>
          <th>Time</th>
          <th>Activity</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>11:10 - 11:39</td>
          <td>Eat Lunch / Gaming</td>
        </tr>
        <tr>
          <td>11:42 - 12:31</td>
          <td>English</td>
        </tr>
        <tr>
          <td>12:35 - 1:23</td>
          <td>Web Design</td>
        </tr>
        <tr>
          <td>All Other Times</td>
          <td>Free Time / Sleep</td>
        </tr>
      </tbody>
    </table>
  </section>
</div>
</body>
</html>
