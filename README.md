# Chapter9AssignmentMusic

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Music Survey Form</title>
  <style>
    body {
      font-family: Verdana, sans-serif;
      max-width: 700px;
      margin: 30px auto;
      background-color: #f7f9fb;
      padding: 20px;
    }
    fieldset {
      border: 2px solid #333;
      padding: 15px;
      margin-bottom: 20px;
      background-color: #fff;
    }
    legend {
      font-weight: bold;
      color: #003366;
    }
    label {
      display: block;
      margin: 8px 0;
    }
    textarea {
      width: 100%;
    }
    footer {
      text-align: center;
      margin-top: 20px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>

  <h2>Music Listening Survey</h2>

  <form action="https://webdevbasics.net/scripts/demo.php" method="post">
    
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email">

    <label for="comments">Why do you enjoy music?</label>
    <textarea id="comments" name="comments" rows="3" cols="60"></textarea>

    <fieldset>
      <legend>Favorite Type of Music</legend>
      <label><input type="radio" name="genre" value="pop"> Pop</label>
      <label><input type="radio" name="genre" value="rock"> Rock</label>
      <label><input type="radio" name="genre" value="jazz"> Jazz</label>
    </fieldset>

    <fieldset>
      <legend>Favorite Artist (Select One)</legend>
      <select name="artist" size="3">
        <option>Taylor Swift</option>
        <option>Drake</option>
        <option>BTS</option>
        <option>Billie Eilish</option>
      </select>
    </fieldset>

    <label for="date">Date you usually listen to music:</label>
    <input type="date" id="date" name="date">

    <br><br>
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">

  </form>

  <footer>
    <p>Created by Joseph Llerena | joseph.llerena@email.com</p>
  </footer>

</body>
</html>
