
UIUC Library Proxy Bookmarklet
------------------------------

I got tired of manually typing in ".proxy2.library.illinois.edu" after the domain when trying to access articles off campus. Here's a quick-and-dirty bookmarklet that'll save you a little typing. Drag this link to your bookmarks bar and click it whenever you're at an article page that requires a login (ACM DL, JSTOR, etc): <a href='javascript:location.href=("https://proxy2.library.illinois.edu/login?url="+location.href);'>Use Library Proxy</a>

If you're on Chrome/Chromium and have your bookmarks bar hidden, hit Ctrl+Shift+B to unhide it.

Here's the javascript snippet it uses:

> javascript:location.href=("https://proxy2.library.illinois.edu/login?url=" + location.href);
Feel free to email me at sunahsuh at illinois dot edu if you encounter issues.
