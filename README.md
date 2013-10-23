smh-paywall-bookmark
====================

SMH Paywall Workaround

If you're hitting the SMH paywall (attached), here's a little trick to view the article you want to read.

1. Create a new bookmark called "SMH" or "AGE"
2. For the URL, paste this code: javascript: (function() { document.getElementById("subscription-overlay").style.display = "none"; document.getElementsByTagName("body")[0].removeAttribute("style"); document.querySelectorAll(".article-counter")[0].style.display = "none"; })()
3. Click the bookmark when you see the paywall overlay.


** UPDATE

Improved DRM has meant that a bookmarklet is not effective. Add an "Block" cookie exception for smh.com.au and theage.com.au in your browser.
