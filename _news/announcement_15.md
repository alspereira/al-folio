---
layout: post
title:  The nexIK project was presented at the SMACUMED International Conference on Water-Energy-Food-Ecosystem Nexus in the Mediterranean Region (WEFE 2023).
date: 2023-11-21 00:00:00-0000
inline: false
---

#### Talk 1: The nexIK Vision: Data-Driven Insights for Energy Efficiency in Industrial Kitchens ####

Hugo Morais delivered a presentation of the nexIK main objectives and provided some insights on the data-driven control of flexible IK devices.

You can find and read the abstract of this talk  [here]({{ site.url }}/assets/post_pdf/announcement_15/WEFE_Abstract_60.pdf){:target="_blank"}.


#### Talk 2: Electricity-Water Nexus Analysis in Industrial Kitchen Appliance Water Consumption ####

Lucas Pereira presented the project findings with respect to estimating the water demand of individual appliances by considering only the aggregated water demand and appliance electricity consumption data.

You can find and read the abstract of this talk  [here]({{ site.url }}/assets/post_pdf/announcement_15/WEFE_Abstract_48.pdf){:target="_blank"}.

<!-- Change the folder inbetween the '' -->
**Photos**
<div class="gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/post_img/announcement_15/' %}
      <div class="gallery-item">
        <img src="{{ image.path | relative_url }}" alt="{{ image.name }}" onclick="showFullscreen(this)">
      </div>
    {% endif %}
  {% endfor %}
</div>

<br/>

<!-- Code for the gallery -->

<!-- Can re-use the code, just change the folder -->


<div class="fullscreen-preview">
  <button type="button" class="close-button" onclick="hideFullscreen()">
    &times;
  </button>
  <button type="button" class="nav-button left-button" onclick="navigateFullscreen(-1)">
    &lt;
  </button>
  <img src="" alt="">
  <p class="subtitle"></p> <!-- Element to display the subtitle -->
  <button type="button" class="nav-button right-button" onclick="navigateFullscreen(1)">
    &gt;
  </button>
</div>

<!-- End of the Gallery with full-screen preview -->

<br/>
<div style="width:100%; text-align:center">
<a href="#" onclick="window.history.back()">Back</a>
</div>
