---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
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

{%for colorA in page.colors %}
  {%for colorB in page.colors %}
  <div class="logo-container" style="">
    <h1
      class="logo"
      style="
        color: white;
        /* background-image: var(--noise-image); */
        /* background-blend-mode: multiply; */
        --box-shadow-color: var(--{{colorB}});
      "
    >
      underline
    </h1>
    <!-- <div style="width: 1000px;top: 100px;left: -465px;margin-top: 0;position: absolute;"><div class="circle blue noisy" style="width: 10%; padding-top: 10%;"></div> -->
    <div class="wave" style="--c:var(--{{colorA}})"></div>
  </div>
  {%endfor%}
{%endfor%}

<div class="container">
  {%for colorA in page.colors %}
  <div class="item"><h3>{{colorA}}</h3></div>
    {%for colorB in page.colors %}
    <div class="item">
      <div class="circle {{colorB}} noisy"></div>
      <div class="circle {{colorA}} noisy"></div>
    </div>
    {%endfor%}
  {%endfor%}
</div>
