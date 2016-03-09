Why Responsive
==============

- Here is a good example of Responsive design and a resource for web developers.
 - http://alistapart.com/

Responsive Design is an art not science. You will have to keep practicing to get better. And there is no one right way to get the job done.

Browserstack
https://www.browserstack.com/

what is difference between simulator and emulator?
browserstack can be used to test our websites on different devices. but its paid service.

link in the course for chrome dev tools:
https://developer.chrome.com/devtools/docs/shortcuts

new updated link here:
https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/shortcuts

we will use chrome dev tools to emulate different devices on your computer.
https://www.youtube.com/watch?v=sDcglPBR34Q
in the video above we can see how to emulate different devices on your chrome browser.

basically go to dev tools in chrome on top right click on the small phoneicon and then select device and test different sites.

---

some interesting links:
======================

should explore these links most of frontend courses cover some interesting stuff about web Fundamentals documentation from here.

google tools:
=============
- https://developers.google.com/web/tools/

web Fundamentals:
=================
- https://developers.google.com/web/fundamentals/?hl=en

Google web:
===========
https://developers.google.com/web/

google developers:
==================
https://developers.google.com/

chrome dev tools:
=================
https://developers.google.com/web/tools/chrome-devtools/

---

access dev tools on window: f12
https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/shortcuts#accessing-devtools

---

how to do remote debugging with android phone and chrome:
(already learned in website optimization course also.)
https://www.udacity.com/course/viewer#!/c-ud893/l-3523969367/m-422278775

https://developers.google.com/web/tools/chrome-devtools/debug/remote-debugging/remote-debugging

---

how to do remote degugging on safari:
https://github.com/google/ios-webkit-debug-proxy

linux and mac needed for this but should checkout the documentation on the repository.

---

lesson 2
========

browser deals with dips: device independent pixels
and hardware deals with : hardware pixels

  both are different: a pixel is not always pixel.

dpi = hardwarepixels/ pixel ratio

---

meta viewport tag used to scale site to device width.

```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag

---

css points: use relative units for width instead of actual lengths

even add this to main css file (recomended):

img, embed, object, video {
   max-width: 100%;
 }

a button should be 48px wide and long to make sure its tappable.
40 pixels of room between any to buttons to make sure not to hit 2 buttons at same time. or miss it completely.

---
```
nav a, button{
  min-width: 48px;
  min-height: 48px;
}
```

---

w3 school css properties list for reference:
https://www.w3.org/community/webed/wiki/CSS/Properties

---

for Responsive design start to plan for smaller screen and keep working up. this is right approach.

steps for making a site Responsive:

1 enter the meta viewport tag.

```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

2 make max width 100% so it does not overflows.:

```
max-width:100%;
```

but cameron did :
```
width:100%
```
changing the actual width from pixels.

3
make buttons touchable easily.
```
nav a, button{
  min-width: 48px;
  min-height: 48px;
}
```

but cameron did

```
padding: 1.5em;
```

4 test layout on different screens.

================
