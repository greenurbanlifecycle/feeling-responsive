---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image_fullwidth: header_frontpage_gulc.jpg 
widget1:
  title: "Was machen wir?"
  url: "/blog/portfolio/"
  image: Ueberblick.jpg
  text: 'In diesem Blog berichten wir über das grüne Leben in der Stadt und wie ihr auch ohne grünen Daumen erfolgreich auf kleinstem Raum Obst und Gemüse anbauen könnt. Wir erklären wie ihr günstig Kompost & Dünger herstellt und mit Problemen wie der richtigen Standortwahl, Ungeziefer und Überwinterung umgeht. Außerdem geben wir euch Tipps wie ihr eure Ernte schnell und einfach zu leckeren, saisonalen Gerichten zubereitet. Und dazu Dinge zum Nachmachen, Nachbasteln und ausprobieren. Viel Spaß:-)'
widget2:
  title: "Warum noch ein Blog?"
  url: '/warum/'
  image: warum_tontis.jpg
  text: 'Was ist "Halbschatten"? Was heißt "nicht zu viel gießen" oder "mäßig gießen"? Weil wir selber unpräzise Angaben aus persönlichen und beruflichen Wegen verabscheuen, wollen wir in diesem Blog möglichst verständliche und deutliche Tipps geben, wie erfolgreich etwas wächst, ohne schon als Botaniker auf die Welt gekommen zu sein. Dabei sollte ebenfalls die humoristische Komponente auch nicht zu kurz kommen.'
widget3:
  title: "Wer & Was sind wir?"
  url: '/contact/'
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
