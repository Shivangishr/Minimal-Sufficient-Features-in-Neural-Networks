{%  if false %}
<!-- 2027-TODO-UPBASE -->
{% endif %}
{% if include.mode == "photos" %}

<div class="row row-cols-1 row-cols-md-2 projects pt-3 pb-3">
  {% include people_horizontal.html name="Leo Schwinn" affiliation="Technical University of Munich" url="https://schwinnl.github.io//" img="assets/img/organizers/ls.jpg" %}
  {% include people_horizontal.html name="Sophie Xhonneux" affiliation="Mila, Université de Montréal" img="assets/img/organizers/sx.jpg" %}
  {% include people_horizontal.html name="Nicholas Gao" affiliation="CuspAI" img="assets/img/organizers/ng.jpg" %}
  {% include people_horizontal.html name="Jonas Köhler" affiliation="CuspAI" img="assets/img/organizers/jk.jpg" %}
  {% include people_horizontal.html name="David Dobre" affiliation="Mila, Université de Montréal" img="assets/img/organizers/dd.jpg" %}
</div>

{% else %}

- David Dobre, Mila, Université de Montréal
- Nicholas Gao, CuspAI
- Jonas Köhler, CuspAI
- Mehrnaz Mofakhami, Mila, Université de Montréal
- Leo Schwinn, Technical University of Munich
- Sophie Xhonneux, Mila, Université de Montréal

{% endif %}
