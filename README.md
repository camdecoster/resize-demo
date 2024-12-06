# Resizing Demo

`index.html` is an HTML slideshow built with [remark][remark].
I would like to modify `mccole.css` to make the SVG diagram 120% of its present size
so that it will be more readable,
but everything I try makes the SVG overlap with the text below it:
it appears that enlarging the SVG via CSS doesn't play nicely with DOM placement.

(Note that I don't want to modify the SVG file itself:
I have several hundred of these,
and they have all been sized for the print edition.
I could convert the SVG to PNG and resize that,
but the 's' in 'SVG' *does* stand for "scalable"…)

[remark]: https://remarkjs.com/