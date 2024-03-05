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

Hello <span class="squiggle" id="name"></span>, come see our new space/hang with us this sunday night at link from 6:30pm onwards.

We've got food, drinks, and some activities planned so please plan to stay for a while.

FAQs:
* Dress code: wear something printed or with squiggly lines (see our social media)
* If you are considering getting us a gift:
    * a small plant for our terrace garden
    * something small we can put on display in our shelf
* We can't have alcohol since it's a commercial property (BYOB _isn't_ allowed either)
* We'll wind up around 10:30pm


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

