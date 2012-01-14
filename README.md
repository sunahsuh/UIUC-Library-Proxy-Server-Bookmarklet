I got tired of manually typing in ".proxy2.library.illinois.edu" after the domain when trying to access articles off campus. Here's a quick-and-dirty bookmarklet that'll save you a little typing. Check out the page at http://sunahsuh.github.com/UIUC-Library-Proxy-Server-Bookmarklet/ for a link you can drag to your bookmarks bar.

Here's the javascript snippet it uses:

> javascript:location.href=("https://proxy2.library.illinois.edu/login?url=" + location.href);

Feel free to email me at sunahsuh at illinois dot edu if you encounter issues.
