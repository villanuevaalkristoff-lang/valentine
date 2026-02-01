# valentine
&lt;I just want to spend Valentine’s Day with you 🌷&lt;/p>
<body>

  <h1>Will you be my Valentine? 💕</h1>

  <p>This comes with love, laughs, and unlimited kilig 😌💖</p>

  <!-- OPTIONS / BUTTONS -->
  <button id="yes" onclick="yesClick()">YES 💖</button>
  <button id="no" onmouseover="moveNo()">NO 😭</button>

  <script>
    function yesClick() {
      document.body.innerHTML =
        "<h1>YAYYY 😭💖</h1><p>Happy Valentine’s Day!</p>";
    }

    function moveNo() {
      const no = document.getElementById('no');
      const x = Math.random() * (window.innerWidth - 100);
      const y = Math.random() * (window.innerHeight - 50);
      no.style.left = x + "px";
      no.style.top = y + "px";
    }
  </script>

</body>
