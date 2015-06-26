Privacy Badger [![Build Status](https://travis-ci.org/EFForg/privacybadgerfirefox.svg)](https://travis-ci.org/EFForg/privacybadgerfirefox)
===================
Privacy Badger blocks spying ads and invisible trackers. It's there to ensure that companies can't track your browsing without your consent.

This extension is designed to automatically protect your privacy from third party trackers that load invisibly when you browse the web. We send the Do Not Track header with each request, and our extension evaluates the likelihood that you are still being tracked. If the algorithm deems the likelihood is too high, we automatically block your browser from responding to the domain. Just because a domain has been flagged by Privacy Badger's algorithm, doesn't mean that that domain is tracking you, just that it could be. 

Our extension has three states. Red means Privacy Badger believes this third-party domain is a tracker, and has blocked it. Yellow means the domain is believed to be both a tracker and necessary for the functioning of the page, so Privacy Badger is allowing it but blocking its cookies to prevent it from uniquely identifying you. Green means that Privacy Badger believes this is not tracker. You can click on the Privacy Badger icon in your browser's toolbar if you wish to override the automatic blocking settings. Or, you can browse in peace as Privacy Badger starts finding and eating up web trackers one by one.

Nothing can stop the Privacy Badger from eating cookies when it's hungry!

Privacy Badger is a project of the Electronic Frontier Foundation.

##Developing
For information on how to develop Privacy Badger read doc/developers_guide.md

##License
Privacy Badger is licensed under the GPLv3. See LICENSE for more details
