---
layout: post
title: Chrome HTTPS Issue
---

Just because I lost like 30 minutes on this problem...

If you are trying to solve insecure content issues working in Chrome, and you seem to have secured all the calls within the page, and other browsers are saying it checks out, but Chrome is still showing you a red slash, so you try clearing your browser history and cache, and it still doesn't work, so you download special web proxy software to try and get to the bottom of it, and _that_ isn't showing anything funny, so you begin digging your fingernails into your cheeks just so you can feel again—

_Solution: Close the tab, and reopen a new tab_

  
Apparently, Chrome caches https errors per tab. Which makes _tons_ of sense.

And which is also great for troubleshooting.
