---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: zb-header.png

widget1:
  title: "Blog"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'A place where I share my latest ventures, thoughts, rambles, schemes and antics. <br/>The trials and tribulations of dabbling late in life with very different career paths; moving from Tech to Art, without a degree or formal schooling beyond GCSE&#39;s, and generally just trying to make life work; keeping afloat with my mental health and my recent diagnosis of Autism at 25.'
widget2:
  title: "Art Portfolio"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'I love to try my hand at a bit of everything, and dabble in <em>a lot</em>: <br/>1. My Painting/Drawings<br/>2. Crafts and DIY projects<br/>3. Videography & Editting: <a href="http://youtube.com/">An Autism webseries I&#39;m working on</a>.<br/>4. Original Music Production & Compsition <br/>5. Tech Work & Projects'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "My Music"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: zb-mymusic-crop.png
  text: 'A very personal hobby of mine that I&#39;ve practised on and off for well over a decade is Music Production. Attempting everything from song writing, composing, vocals and instruments; I&#39;ve only recently starting releasing my work publicly, under my other pseudonym <em>Zoeseph</em>.'
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
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
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
