---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: MengAurora.jpg
widget1:
  title: "Vision"
  url: '/vision/'
  image: AIcycle.png
  text: "Read about the SkAI Institute's vision for the future of AI in astronomy"
widget2:
  title: "People"
  url: '/directory/'
  text: 'Meet the people and institutions behind the SkAI Institute'
  image: logo_skai.png
widget3:
  title: "News & Events"
  url: '/newsandevents/'
  image: widget-github-303x182.jpg
  text: 'Recent SkAI news and upcoming events'

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
  text: Sign up to stay informed of new SkAI developments ›
  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
