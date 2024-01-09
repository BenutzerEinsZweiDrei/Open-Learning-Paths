---
title: Bookmarklets
---

# [Bookmarklets](http://en.wikipedia.org/wiki/Bookmarklet)

I run my bookmarklets from KM like so:

![](https://i.imgur.com/UIQNrjr.png)

## Bookmarklets I use

- [Go to first commit of currently open repo](#code)
- [Online article discussion finder](https://github.com/theoretick/discuss-it) - Lets you see where the link you are watching right now has been discussed before.

## Notes

- You can add bookmarklets in Safari either by:
  1. Dragging a bookmarklet from a webpage to your bookmarks bar then moving it from there.
  2. Creating a random bookmark, then editing it and changing the URL to the bookmarklet JavaScript.

## Code

Go to initial commit on GitHub repo. Must have GitHub repo open in active tab.

```js
javascript: ((b) =>
  fetch("https://api.github.com/repos/" + b[1] + "/commits?sha=" + (b[2] || ""))
    .then((c) => Promise.all([c.headers.get("link"), c.json()]))
    .then((c) => {
      if (c[0]) {
        var d = c[0].split(",")[1].split(";")[0].slice(2, -1);
        return fetch(d).then((e) => e.json());
      }
      return c[1];
    })
    .then((c) => c.pop().html_url)
    .then((c) => (window.location = c)))(
  window.location.pathname.match(/\/([^\/]+\/[^\/]+)(?:\/tree\/([^\/]+))?/)
);
```

## Links

- [Powerlet](https://github.com/anthonyec/powerlet) - Chrome Extension to quickly find and run bookmarklets.
- [Awesome Bookmarklets](https://github.com/marcobiedermann/awesome-bookmarklets)
- [Awesome Userscripts](https://github.com/bvolpato/awesome-userscripts) ([HN](https://news.ycombinator.com/item?id=29054673))
- [Userscripter](https://github.com/SimonAlling/userscripter) - Create userscripts in a breeze.
- [Cherry](https://github.com/kidonng/cherry) - Collection of handcrafted resources.
- [Scriptbar Snippets](https://scriptbar-snippets.tryapp.us/) - Handy and easy to understand snippets to keep in your browser. ([Code](https://github.com/datduyng/scriptbar-snippets))
- [userscript.zone](https://www.userscript.zone/) - Search for userscripts by URL, domain or search term. ([HN](https://news.ycombinator.com/item?id=31566061))
- [HN Anti Paywall](https://github.com/MostlyEmre/hn-anti-paywall) - Userscript that adds archive URLs below the paywalled HN submissions. ([HN](https://news.ycombinator.com/item?id=33794672))
- [Hacker News userscript to make this site more legible](https://github.com/mgladdish/website-customisations/tree/main/news.ycombinator.com) ([HN](https://news.ycombinator.com/item?id=34037462))
- [Bookmarklet Editor](https://www.gibney.org/bookmarklet_editor) ([Lobsters](https://lobste.rs/s/3jgneb/my_bookmarklet_editor))
- [esbuild-plugin-bookmarklet](https://github.com/reesericci/esbuild-plugin-bookmarklet) - Esbuild plugin to generate bookmarklets.
