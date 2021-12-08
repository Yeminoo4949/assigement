<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div>
        <button id="i" onclick="i()">increase</button>
        <button id="j" onclick="j()">decrease</button>
    </div>
    <p id="result"></p>

    <script>
         let k = 0;

function i() {
  k++;
  document.getElementById('result').innerHTML = k;
}
function j() {
  k--;
  document.getElementById('result').innerHTML = k;
}
    </script>
</body>
</html>
