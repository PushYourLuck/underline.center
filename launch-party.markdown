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
title: Launch Party
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

# Hello <span class="squiggle" id="name"></span>

We'd love to show you what we've been working on the past few months. This space is nothing without the people and community to fill it, and you are needed to help make it _our_ space.

**Join us this Sunday at 6:30pm at the <a href="https://maps.app.goo.gl/qa4yF16LJ7cGSE6EA" target="_blank">Underline Center</a>**.

We've got food, drinks, games, and other activities so please plan to stay for a while.

With love and squiggles,<br>Punjit & Karthik

# FAQs:
* We won't have any alcohol since it's a commercial property (BYOB _isn't_ allowed either)
* We will wrap up by 10:30pm
* Suggested dress code: Anything with prints, squiggly lines, or abstract shapes and colors.
* If you are considering getting us a gift, we'd prefer:
    * a small shade-friendly plant for our terrace garden
    * something small we can put on display in our main shelf


<script>
const queryParams = new URLSearchParams(window.location.search);
const name = atob(queryParams.get('~') || 'ZnJpZW5k').replace(/[<\>]+/g, '');

const el = document.getElementById('name');
el.innerHTML = name;

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

