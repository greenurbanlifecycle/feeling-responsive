---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Palmen.jpg 
widget1:
  title: "Was machen wir?"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: Ueberblick.jpg
  text: 'In diesem Blog berichten wir über das grüne Leben in der Stadt und wie ihr auch ohne grünen Daumen erfolgreich auf kleinstem Raum Obst und Gemüse anbauen könnt. Wir erklären wie ihr günstig Kompost & Dünger herstellt und mit Problemen wie der richtigen Standortwahl, Ungeziefer und Überwinterung umgeht. Außerdem geben wir euch Tipps wie ihr eure Ernte schnell und einfach zu leckeren, saisonalen Gerichten zubereitet. Und dazu Dinge zum Nachmachen, Nachbasteln und ausprobieren. Viel Spaß:-)'
widget2:
  title: "Why use this theme?"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: '<em>Feeling Responsive</em> is heavily customizable.<br/>1. Language-Support :)<br/>2. Optimized for speed and it&#39;s responsive.<br/>3. Built on <a href="http://foundation.zurb.com/">Foundation Framework</a>.<br/>4. Seven different Headers.<br/>5. Customizable navigation, footer,...'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Wer & Was sind wir?"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: Logo1_2.png
  text: 'Als Ingenieure sind wir in erster Linie Software Entwickler und Gärtnern stellt einen Ausgleich zu den langen Tagen vor unseren Monitoren dar. Auch wenn unsere Ausbildung nichts mit Gärtnern zu tun hat, haben wir gelernt Dinge zu hinterfragen und teils kreative Lösungen für Probleme zu suchen. Wir lieben es zu kochen, verrückte Dinge auszuprobieren und Probleme zu lösen. Auf diese Weise möchten wir unsere Ideen und Erfahrungen mit euch teilen. '
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
  text: Wollt ihr auf dem Laufenden bleiben? Hier gehts zum Newsletter... ›
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
