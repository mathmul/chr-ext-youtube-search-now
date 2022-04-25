# chr-ext-youtube-search-now

This extension has two stages.

In the first stage it checks whether a newly opened tab is a secure YouTube site
(https://www.youtube.com or https://youtube.com). If it is not, it does nothing,
and that's it.

In the second stage ie. if it _is_ a secure YouTube site, all it does is the
following:
```
// Prints this comment to console
console.log('search focused by extension')
// Finds the first <input> element with id="search", and focuses it so you can
// immediately start typing.
document.querySelector('input#search').focus()
```

The extension needs no additional permissions, nor does it collect any data.
