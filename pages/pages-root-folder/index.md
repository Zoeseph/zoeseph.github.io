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
  url: 'http://zoeseph.github.io/blog/'
  image: typewriter_960_720.jpg
  text: 'I have always wanted to create and ripple social impact through my work, and always thought that a good platform to share my thoughts and ideas, would be starting off with a website. After many <em>many</em> years of saying I would but not doing anything (thanks Executive Dysfunctioning due to undiagnosed ASD) may I please happily & excitedly present to all of my lovely site <br/>visitors; Zo Blogg&#39;s Blog.'

    
widget2:
  title: "My Music"
  url: 'http://zoeseph.github.io/music'
  image: foglogoz.png
  text: 'A very personal hobby of mine that I&#39;ve practised on and off for well over a decade is Music Production. <br/>Attempting everything from song writing, composing, vocals and instruments; I&#39;ve only recently starting releasing my work publicly, under my other pseudonym <em>Zoeseph</em>.'
  
widget3:
  title: "Art Portfolio"
  url: 'http://zoeseph.github.io/art/'
  image: painter-1937575_960_720.jpg
  text: 'I forgot my love for painting and drawing until recently so I am finally spending time on creating again. Various art styles I enjoy consuming include; woodcut style illustration drawings, impressionism and post impressionism, clever use of negative space and contrasting vibrant colours and textures. I also enjoy various tattoo styles including traditional japanese, stippled fine art, and various takes neo-traditional portraits and animals.'



widget4:
  title: "DIY & Crafts"
  url: 'http://zoeseph.github.io/diy-crafts/'
  image: tools-498202_960_720.jpg
  text: 'As a child I dreamt of becoming an Inventor. Ever fascinated by non-electrical tools & appliances, and the engineering behind such staple items, like the hand crank sewing machines, which still stand the test of time over 100 years later, rigid heddle loom weaves, and the general intricacies of gear-train driven devices. To this day, my imagination is still wild that I&#39;m constantly creating or drawing contraptions that don&#39;t exist but should, and either aid daily life, or make it more practical in some way. I was overwhelmed with joy when coming across the term “maker”...'


  
widget5:
  title: "Tech Projects"
  url: 'http://zoeseph.github.io/tech/'
  image: raspiandmic.jpg
  text: 'As a Hardware & Software Technician/Engineer turned Software Engineer, who then specialised in Data Analysis, I then altogether left the IT industry to focus on self discovery and to better serve the creativity I was so desperately seeking and <em>needed</em> within my roles and work, but couldn’t find. <br>I’ve always wanted to create Social Impact through my work, so, as a start, have recently started to explore more artistic ventures through games programming.'



widget6:
  title: "Autism"
  url: 'http://zoeseph.github.io/autism'
  text: 'In the early summer of 2018, after years of battling mental health issues, and the ripple of problems they can create and affect; I was diagnosed with ASD (Autism) at 25 years old. <br/>This is a safe space I have created in order to share the journey of the last year, and how it has changed my perspective on many aspects of life, my attitude, all the up&#39;s and down&#39;s in between, but ultimately how I am trying to manage my life, and move forward with a positive mindset. '
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://zoeseph.github.io/images/brainy.png" width="302" height="182" alt=""/></a>'


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
  url: https://tinyletter.com/zobloggs
  text: for super secret updates and special early announcements ›
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
