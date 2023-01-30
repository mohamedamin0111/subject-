<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>اهلا ابله نهاد</title>
    <style>
      body {
        background-color: lightgray;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        font-family: "Cairo", sans-serif;
      }

      button {
        background-color: green;
        color: white;
        padding: 20px;
        border-radius: 10px;
        font-size: 22px;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <button id="myButton">أضغطي علي الزر</button>
    <script>
      document.getElementById("myButton").addEventListener("click", function() {
        alert ("هناخد امتي 3 اعدادي");
      });
    </script>
  </body>
</html>
