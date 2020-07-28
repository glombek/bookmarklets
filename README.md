# Useful bookmarklets
Drag and drop to your bookmarks bar/menu to install and click to apply these tweaks to the current webpage.

## General use
<a href="javascript:document.querySelectorAll("[id]").forEach(e => { var a = document.createElement('a'); a.href = "#" + e.id; a.text = "#"; e.prepend(a);});">Show # links</a>

## Web development
<a href="javascript:document.querySelectorAll("[class]").forEach(e => e.className = "");">Remove all classes</a>
