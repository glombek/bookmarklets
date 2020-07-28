# Useful bookmarklets
Drag and drop to your bookmarks bar/menu to install and click to apply these tweaks to the current webpage.

## General use
[Show # links](javascript:document.querySelectorAll\("[id]"\).forEach(e => { var a = document.createElement\('a'\); a.href = "#" + e.id; a.text = "#"; e.prepend\(a\);});)

## Web development
<a href="javascript:document.querySelectorAll("[class]").forEach(e => e.className = "");">Remove all classes</a>
