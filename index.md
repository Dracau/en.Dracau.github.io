---
layout: categories
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.3
  overlay_image: /assets/images/tentacle-draft-1.gif
excerpt: >
  My portfolio
row1:
  - image_path: /assets/images/GT-fighting-game.png
    alt: "Personal Projects"
    title: "Personal Projects"
    excerpt: >
      Projects carried out in a personal context, alone or with friends..
    btn_label: "<i class='fas fa-info-circle'></i> En savoir plus"
    btn_class: "btn--primary"
    url: /projets-personnels/

row2:
  - image_path: /assets/images/ecoles.png
    alt: "School projects"
    title: "School projects"
    excerpt: >
      Projects carried out in a school context, at Rubika or the CNED.
    btn_label: "<i class='fas fa-info-circle'></i> En savoir plus"
    btn_class: "btn--primary"
    url: /projets-scolaires/

---

{% include feature_row id="row1" type="left" %}

{% include feature_row id="row2" type="right" %}
