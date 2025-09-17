---
layout: fullpage
colors: 
  - red
  - orange
  - aqua
  - green
  - yellow
  - teal
  - pink
  - blue
  - black
title: Launch Party
---

 <link rel="stylesheet" href="assets/default.min.css">

<style>
    #wrapper {
        margin: 0px;
        padding: 0px;
        width: 100%;
        height: 100%;
        position: absolute;
        left: 0%;
        top: 0%;
        blend-mix-mode: multiply;
      }

      #wrapper ul {
        width: 100%;
        height: 100%;
        margin: 0px;
        padding: 0px;
      }

      #wrapper li {
        list-style: none;
        font-size: 3em;
        background: #ffffff1c;
        position: absolute;
        top: 0%;
        left: -100px;
        animation: square 13s ease-in infinite;
        text-align: center;
        vertical-align: middle;
      }

      #wrapper li:nth-child(1) {
        top: 10%;
        font-size: 4em;
        animation-delay: 2s;
      }

      #wrapper li:nth-child(2) {
        top: 40%;
      }

      #wrapper li:nth-child(3) {
        top: 60%;
        animation-delay: 3s;
      }

      #wrapper li:nth-child(4) {
        top: 80%;
        animation-delay: 5s;
      }

      #wrapper li:nth-child(5) {
        top: 50%;
        font-size: 3em;
        animation-delay: 8s;
      }

      #wrapper li:nth-child(6) {
        top: 60%;
        font-size: 3.3em;
        animation-delay: 6s;
      }

      #wrapper li:nth-child(7) {
        top: 80%;
        font-size: 4em;
        animation-delay: 3s;
      }

      #wrapper li:nth-child(8) {
        top: 30%;
        animation-delay: 7s;
      }

      @keyframes square {
        from {
          transform: rotate(0deg);
        }
        to {
          left: 100%;
          transform: rotate(500deg);
          opacity: 0.4;
        }
      }
</style>

<div id="mycountdown" class="my-countdown simply-countdown"></div>



<script src="assets/simplyCountdown.umd.js"></script>
<script>
    simplyCountdown("#mycountdown", {
        year: 2025, // Target year (required)
        month: 3, // Target month [1-12] (required)
        day: 23, // Target day [1-31] (required)
        hours: 17, // Target hour [0-23], default: 0
        minutes: 46, // Target minute [0-59], default: 0
        seconds: 30, // Target second [0-59], default: 0
        countUp: true
    });
</script>

