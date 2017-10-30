# buttonFunc
button function using css and js
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="index.css" rel="stylesheet" type="text/css" />
    <style>
      button{
  height:95px;
  width: 95px;
  background: #7b4397;
  color: white;
  border-radius: 20%;
  text-align: center;
}
button:hover{
  transform: translate(175px);
  background-color: teal; 
  /*linear-gradient(to right, teal, #283e51);*/
}
#animated{
  transition:transform 1s ease-in 1.5s, background-color 1s linear;
} 
    </style?
  </head>
  <body>
    <button id="animated" onclick="xquestion();">cick for question</button>
    <script>
      function xquestion(){
        var x=prompt("the answer is: 'here'");
          if(x==='here'){
          alert('You are corect');
          }
      }
    </script>
  </body>
</html>
