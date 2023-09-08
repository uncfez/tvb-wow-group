---
title: "Welcome to Bonanza 2023 in Umeå!"
date: "2023-03-27"
categories: 
  - "bonanza"
---

**Turf Bonanza Umeå 20 May 2023**

<!DOCTYPE HTML>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
p {
  text-align: center;
  font-size: 50px;
  margin-top: 0px;
}
</style>
</head>
<body>

<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("May 20, 2023 10:00:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();
    
  // Find the distance between now and the count down date
  var distance = countDownDate - now;
    
  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
  // Output the result in an element with id="demo"
  document.getElementById("demo").innerHTML = days + " : " + hours + " : "
  + minutes + " : " + seconds + " ";
    
  // If the count down is over, write some text 
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "BONANZA!";
  }
}, 1000);
</script>

</body>
</html>

### Anmälda hittills/ Registered so far

\[COUNTER\_NUMBER id=2383\]

## Missa inte den nordligaste Bonanzan någonsin *\** Don't miss the northernmost Bonanza ever

## [**Läs mer och anmäl dig (svenska)**](https://www.turfvasterbotten.se/bonanza/valkommen-bonanza-2023)

## [**Read more and register (english)**](https://www.turfvasterbotten.se/bonanza/welcome-bonanza-2023)

### Deltagare / Participants per region

\[COUNTER\_NUMBER id=2387\]
