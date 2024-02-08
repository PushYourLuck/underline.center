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
  <div style="display:inline-block;">
    <div style="width:400px;height:auto;display:inline-block;">
      {% include logo/underline-svg.html logo_color=colorA squiggle_color=colorB %}
    </div>
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
