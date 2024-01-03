---
layout: categories
permalink: /
hidden: false
header:
  overlay_color: "#5e616c"
  overlay_filter: 0.3
  overlay_image: /assets/images/tentacle-draft-1.gif
excerpt: >
  Welcome to my portfolio !

row1:
  - image_path: /assets/images/ecoles.png
    alt: "Professional projects"
    title: "Professional projects"
    excerpt: >
      Projects carried out in a professional context.
    btn_label: "<i class='fas fa-info-circle'></i> See more"
    btn_class: "btn--primary"
    url: /projets-professionnels/

row2:
  - image_path: /assets/images/ecoles.png
    alt: "School projects"
    title: "School projects"
    excerpt: >
      Projects carried out in a school context, at Rubika or the CNED.
    btn_label: "<i class='fas fa-info-circle'></i> See more"
    btn_class: "btn--primary"
    url: /projets-scolaires/

row3:
  - image_path: /assets/images/GT-fighting-game.png
    alt: "Personal Projects"
    title: "Personal Projects"
    excerpt: >
      Projects carried out in a personal context, alone or with friends.
    btn_label: "<i class='fas fa-info-circle'></i> See more"
    btn_class: "btn--primary"
    url: /projets-personnels/

---

{% include feature_row id="row1" type="left" %}

{% include feature_row id="row2" type="right" %}

{% include feature_row id="row3" type="left" %}
