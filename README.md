# What this is
This is a special designed gadget to load iFrames after the page loads, thus not affecting the page load speed. 
# Why does this affect the page load speed
Instead of trying to load text, images, iFrames, scripts, etc., at the same time, why not give priority to the most important elements?
iFrames often can be loaded after, right? As well as certain images, so users don't spend 3 years waiting for the page to load!
This waits 1.5 second ( definitely enough time for a page to load) then document.write the iFrame ( sadly you can only define the src )
# How to use this
It is easy. No coding is required from you. We don't use ads, analytics, nor cookies. We only use javascript to offer you the best experience.
(Actually there is a jQuery librarey hanging around... let me delete that real quick.)
Just embed https://chiefchippy2.github.io/Loading?url=(enter url here) and that is it. By default, it is an iFrame of a random youtube video.
Be sure to enter a correct URL ( it can be escaped but it is not obligatory). You can use it as you want.
