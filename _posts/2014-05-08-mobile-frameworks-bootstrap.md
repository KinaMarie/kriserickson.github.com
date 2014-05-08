---
layout: post
title: "Mobile Frameworks -- Bootstrap"
description: "Bootstrap is another monster in the mobile world now, especially with Bootstrap 3.0 and its emphasis on responsive and
mobile first design.  And it can't be argued that it is popular, a lot of the sites you see created in the past few
years are written with the aid of Bootstrap (or perhaps Zurb's Foundation)). It provides
a great way to get a website up and going, and looking good with as ..."
category: 
tags: []
---
{% include JB/setup %}

This is Part 4 in multipart series on the State of Mobile Frameworks in 2014, see [Part 1](/programming/2014/04/22/the-state-of-html-mobile-frameworks-in-2014/),
[Part 2](http://www.agingcoder.com/programming/2014/04/24/mobile-frameworks-jqt/) and [Part 3](http://www.agingcoder.com/programming/2014/04/26/mobile-frameworks-jquery-mobile/)
if you haven't already.

Bootstrap is another monster in the mobile world now, especially with Bootstrap 3.0 and its emphasis on "responsive" and
"mobile first" design.  And it can't be argued that it is popular, a lot of the sites you see created in the past few
years are written with the aid of Bootstrap (or perhaps [Zurb's Foundation](http://foundation.zurb.com/)).  It provides
a great way to get a website up and going, and looking good with as little effort as possible, and with its prevelence
on the web it provides a familiar comforting look and feel to the site.  And mobile websites (not apps) properly
designed look and feel fantastic, however when run as app on a phone or tablet it really feels like a website packaged
for that device.

**How it Works**

While Bootstrap will work with just css (unlike, say jQuery mobile), it requires jQuery and Bootstrap's own javascript
files to gain access to some of the more powerful Bootstrap functionality like transitions, modals, dropdowns,
tabs, tooltips, etc.  You decorate your elements with Bootstrap classes (as well as the default css that Bootstrap
provides) to provide the functionality.  After a short learning curve you will be creating sites that can work
well both phones, tablets and desktops.  However, you will have to take a bit of care in your design depending on
your site to get a proper mobile experience that doesn't feel like scrolling safari as responsive design requires
more than a simple framework to make it successful, you have to spend some time designing how the experiences should
work.  However, all that said, while Bootstrap makes very nice mobile websites they look like website and not
apps.  This is the main problem with using Bootstrap to create a mobile app, is that you have to make fairly radical
changes to the Bootstrap css and javascript to get the feeling of app rather than a website.  That said, the
Twitter Bootstrap folks have recently pushed [Ratchet](http://goratchet.com/) which was initially an IOS prototyping
tool, the latest version looks like something to keep an eye on in the mobile app space.

**Advantages**
- Easy to use
- Very popular, hundreds or thousands of Bootstrap themes are available as well as hundreds of plugins.
- Modern looking, constantly updated, and has a very nice web ascetic.
- Nicely documented.

**Disadvantages**
- Looks like a website, not an app.
- Requires lots of changes to the css and js to get the appearance of an app, which makes it difficult to upgrade.
- While it is

**Summary**

Next up, KendoUI Mobile...

