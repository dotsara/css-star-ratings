:star2: one of my [100 projects](https://github.com/dotsara/100-projects) :star2:

# css star ratings
## A little CSS-based star-rating module

:clapper: [css-star-ratings in action](http://toolbox.dotsara.com/css-star-ratings) :clapper:

### Notes

* Well, _first_ I tried to make this happen with a `<ul>`, but I learned very quickly that the `unicode-bidi: bidi-override` and `direction: rlt` combo don't do the _kind_ of reversal I wanted here. What they do on a `<ul>` is flip the position of the bullet, which is good to know, but it wasn't what I wanted, so fine! `<span>`s it is.
* [CSS Tricks: Star Ratings With Very Little Code](https://css-tricks.com/star-ratings/) is the basis of the bulk of the CSS here. I added [flexbox display](http://learnlayout.com/flexbox.html) to the `.rating` container so that there wouldn't be those annoying little gaps between the star `<span>`s. (I've seen the workarounds for hacking that space and they all look like a nightmare for long-term maintenance.)
* Once again, I tinkered around in [Jackson](http://jxnblk.com)'s [Spectral app](http://jxnblk.com/Spectral/#0022fc&hues=4&rows=3&shiftS=-0.1&shiftL=-0.1) to choose colors for the stars. :+1: