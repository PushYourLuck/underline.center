---
layout: underline
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
title: UC turns one!
---

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

# It's our first birthday

We're hosting a small gathering at 8:30pm this Friday, February 28th and we want to celebrate it with you <span class="squiggle" id="name1"></span>.

We set out to build a warm and welcoming community space, and it wouldn't have been possible without you. So please come hang out with us and celebrate as we look ahead at the upcoming year.

With love and squiggles,<br>Punjit & Karthik

# FAQs

- 🚫 We won't have any alcohol since it's a commercial property (BYOB _isn't_ allowed either)
- 🕥 We will wrap up by 11pm

<script>
const queryParams = new URLSearchParams(window.location.search);
const name = atob(queryParams.get('~') || 'ZnJpZW5k').replace(/[<\>]+/g, '');

const el1 = document.getElementById('name1');
el1.textContent = name;
  
</script>

<!-- <div id="wrapper">
    <ul>
    {%for colorA in page.colors %}
       <li class="squiggle" style="">👕</li>
    {%endfor%}
      <li class="squiggle">👕</li>
      <li class="squiggle">👖</li>
      <li class="squiggle">🧦</li>
      <li class="squiggle">😴</li>
      <li class="squiggle">🍵</li>
      <li class="squiggle">💤</li>
      <li class="squiggle">👕</li>
      <li class="squiggle">👖</li>
    </ul>
  </div> -->
