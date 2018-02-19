---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth
header:
  image_fullwidth: galaxy.jpg
title:  "Net Neutrality"
subheadline: "Internet Freedom"
teaser: "We are living in a world where <b>net neutrality</b> is not always guaranteed. <br />While there is even no such a thing in some countries, some other country is stupid enough to follow suit.
<br /><b>Without</b> net neutrality, certain contents or services might get slowed down or completely blocked by Internet service providers."
breadcrumb: true
layout: frontpage
widget1:
  title: "What is Net Neutrality"
  url: 'https://true-net-neutrality.github.io/violations-of-net-neutrality/'
  image: balance.jpg
  <!--image: widget-1-302x182.jpg-->
  text: '<a href="https://en.wikipedia.org/wiki/Net_neutrality">Net neutrality</a> is the principle that governments should mandate Internet service providers to treat all data on the Internet the same, and not discriminate or charge differently by user, content, website, platform, application, type of attached equipment, or method of communication.'
widget2:
  title: "How to restore Net Neutrality?"
  url: 'https://true-net-neutrality.github.io/solution/'
  image: mesh.jpg
  text: 'What if we connect every nearby mobile devices directly and bypass every cell phone tower. Yes you are right! Short-Range Wireless Communication technologies such as <a href="https://developer.apple.com/documentation/corebluetooth">BLE</a> and <a href="https://developer.android.com/guide/topics/connectivity/wifip2p.html">WifiP2P</a>, might be the <b>cure</b>.'
widget3:
  title: "Fun Apps using BLE/WifiP2P"
  url: 'https://true-net-neutrality.github.io/fun-apps/'
  image: app_store.jpg
  <!--image: widget-github-303x182.jpg-->
  text: 'Short-Range Wireless Communication can also be fun. Check out the following apps: <br />1. <a href="https://itunes.apple.com/us/app/hi-there-p2p/id1276567474?ls=1&mt=8">HiThere</a>: A proximity based face-to-face dating app. <br />2. <a href="https://play.google.com/store/apps/details?id=com.wifidirect.ble.seanxu.guesswhat">Guess What</a>: A near range message sharing tool.'
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
