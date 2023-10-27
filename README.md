<!DOCTYPE html>
<html>
<head>
  <title>Inline Color Change</title>
  <script>
    let colors = ["red", "orange", "yellow", "green", "blue", "purple"];
    let i = 0;
    
    function changeColor() {
      let header = document.getElementById("header");
      header.style.color = colors[i];
      
      i = (i + 1) % colors.length; // Cycle through the colors array
      setTimeout(changeColor, 1000); // Change color every 1 second
    }
    
    window.onload = changeColor; // Start changing color on page load
  </script>
</head>
<body>
  <h1 id="header" style="display: inline;">Marcus Peterson</h1>
</body>
</html>

<a href="https://git.io/streak-stats"><img src="https://github-readme-streak-stats.herokuapp.com?user=Marcus-Peterson" alt="GitHub Streak" /></a>
