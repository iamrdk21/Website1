---
layout: post
title: First post!
image: /img/hello_world.jpeg
---

This is my first post, how exciting!
  
<head>
  <!-- add the button style & script -->
  <link rel="stylesheet" href="../css/applause-button.css" />
  <script src="../js/applause-button.js"></script>
  <style>
    applause-button {
      width: 58px;
      height: 58px;
      margin-top: 40px;
      margin-left: 40px;
    }
  </style>
</head>
<body>
  <applause-button id="applause" multiclap="true" url="google.com"/>
  <script type="text/javascript">

    const button = document.getElementById("applause");

    button.initialClapCount.then(function(count) {
      console.log("initial clap count", count);
    });

    button.addEventListener("clapped", function(event) {
      console.log("button clapped", event.detail);
    });
  </script>
</body>
