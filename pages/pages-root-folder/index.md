---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Background"
  url: "/background/"
  image: widget_hospital_background.jpg
  text: >
    Learn why we are building an emergency department LLM simulation and how Canadian ED pressures shape our work.
widget2:
  title: "Teams"
  url: "/team/academia/"
  image: DenosLab.jpg
  text: >
    Meet the collaborators engineering our emergency department simulations and supporting deployments.
widget3:
  title: "Publications"
  url: "/publications/"
  image: widget-github-303x182.jpg
  text: >
    Dive into our peer-reviewed papers and preprints showcasing how LLMs can enhance emergency department practice.
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
