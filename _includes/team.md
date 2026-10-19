{%  if false %}
<!-- 2027-TODO-UPBASE -->
{% endif %}
{% if include.mode == "photos" %}

<div class="row row-cols-1 row-cols-md-2 projects pt-3 pb-3">
  {% include people_horizontal.html name="Leo Schwinn" affiliation="Technical University of Munich" url="https://schwinnl.github.io//" img="assets/img/organizers/ls.jpg" %}
  {% include people_horizontal.html name="Sophie Xhonneux" affiliation="Mila, Université de Montréal" img="assets/img/organizers/sx.jpg" %}
  {% include people_horizontal.html name="Nicholas Gao" affiliation="CuspAI" img="assets/img/organizers/ng.jpg" %}
  {% include people_horizontal.html name="Jonas Köhler" affiliation="CuspAI" img="assets/img/organizers/jk.jpg" %}
  {% include people_horizontal.html name="Yan Scholten" affiliation="Technical University of Munich" img="assets/img/organizers/ys.jpg" %}
  {% include people_horizontal.html name="Quentin Bertrand" affiliation="Inria" img="assets/img/organizers/qb.jpg" %}
  {% include people_horizontal.html name="Rémi Emonet" affiliation="Hubert Curien Laboratory,  University of Saint-Étienne, Inria" img="assets/img/organizers/re.jpg" %}
</div>

{% else %}

- Nicholas Gao, CuspAI
- Jonas Köhler, CuspAI
- Mehrnaz Mofakhami, Mila, Université de Montréal
- Leo Schwinn, Technical University of Munich
- Sophie Xhonneux, Mila, Université de Montréal
- Yan Scholten, Technical University of Munich
- Quentin Bertrand, Inria
- Rémi Emonet, Université Jean Monnet

{% endif %}
