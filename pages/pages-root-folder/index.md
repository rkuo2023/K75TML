---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_homepage_13.jpg
widget1:
  title: "Game Guides"
  url: 'http://rkuo2023.github.io/K75TML/guides/game-guides/'
  image: widget-1-302x182.jpg
  text: 'Game guides for players'
  video: '<iframe width="220" height="123" src="https://www.youtube.com/embed/bMkINbwzslw" title="Misty Continent: Cursed Island Tips" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>'
widget2:
  title: "Event Guides"
  url: 'http://rkuo2023.github.io/K75TML/events/alliance-crunch/'
  text: '<em>Main Events</em>: <br/>1. Alliance Crunch <br/>2. Ancient Gate <br/>3. Specter Raid <br/>4. Relic War <br/>5. Tidelands <br/>6. Crown Invasion <br/>...'
  video: '<iframe width="220" height="123" src="https://www.youtube.com/embed/oYjoYuiQ9Bc" title="Misty Continent - PVP [Every player should know] #stormshot (Eng Version)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>'
widget3:
  title: "Combat Tactics"
  url: 'http://rkuo2023.github.io/K75TML/tactics/combat-tactics/'
  image: widget-github-303x182.jpg
  text: '<em>Combat Tactics</em>: <br/>1. Solo-Attack <br/>2. Rally-Attack <br/>3. Self-Defense <br/>4. Group-Defense <br/>...'
  video: '<iframe width="220" height="123" src="https://www.youtube.com/embed/oYjoYuiQ9Bc" title="Misty Continent - PVP [Every player should know] (Eng Version)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>'
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
  url: https://rkuo2023.github.io/K75TML
  text: [homepage]
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
