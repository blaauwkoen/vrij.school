<html>
<head>
  <meta content="width=device-width, initial-scale=1" name="viewport">
  <link rel="stylesheet" href="assets/styles.css">
  <script type="text/javascript" src="assets/countdown.js"></script>
  <link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,600,900" rel="stylesheet">
</head>
<body id="geenmeivakantie" style="display:none; background-color: #FF014F;">
<div class="content">
<h1>😣</h1>
<h2>Je hebt geen vakantie</h2>
<p>nog <div id="totmeivakantie"></div> dagen tot de meivakantie</p>
</div>
<div><p class="footer">Website door <a href="http://ko3n.nl">Koen Blaauw</a></p>
</body>
<body id="welmeivakantie" style="display:none; background-color: #00DA73;">
<div class="content">
<h1>🎉</h1>
<h2>Je hebt vakantie!</h2>
<p>nog <div id="nogmeivakantie"></div> dagen vakantie</p>
</div>
<div><p class="footer">Website door <a href="http://ko3n.nl">Koen Blaauw</a></p>
</body>
<body id="geenzomervakantie" style="display:none; background-color: #FF014F;">
<div class="content">
<h1>😣</h1>
<h2>Je hebt geen vakantie</h2>
<p>nog <div id="totzomer"></div> dagen tot de zomervakantie</p>
</div>
<div><p class="footer">Website door <a href="http://ko3n.nl">Koen Blaauw</a></p>
</body>
<body id="welzomervakantie" style="display:none; background-color: #FF014F;">
<div class="content">
<h1>🎉</h1>
<h2>Je hebt vakantie!</h2>
<p>nog <div id="nogzomer"></div> dagen</p>
</div>
<div><p class="footer">Website door <a href="http://ko3n.nl">Koen Blaauw</a></p>
</body>


<script>
window.setInterval(function(){

  var current = new Date();
  var beginmei  = new Date("April 28, 2018 00:00:01")
  var eindmei = new Date("May 6, 2018 00:00:01")
  var beginzomer = new Date("July 21, 2018 00:00:01")

  if(current.getTime()>beginmei.getTime()){
    $('#totmeivakantie').hide();
    $('#welmeivakantie').show();
  }
  else if(current.getTime()>eindmei.getTime()){
       $('#welmeivakantie').hide();
       $('#geenzomervakantie').show();
   }
  else if(current.getTime()>beginzomer.getTime()){
       $('#geenzomervakantie').hide();
       $('#welzomervakantie').show();
   }

}, 3000);

$('#one').show();</script>
</html>
