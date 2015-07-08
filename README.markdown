Bad Fox
========

A color scheme for Vim, forked from Bad Wolf by [Steve Losh](http://stevelosh.com/).

Feel free to send me ideas through the [issue tracker][] or pull requests.

It's MIT/X11 licensed, so feel free to hack it apart if you like.

**If you're going to send a pull request that you want me to merge, please post
a comment in it with before/after screenshots!**

[issue tracker]: http://github.com/viccuad/badfox/issues

Configuration
-------------

There are a few settings you can use to tweak how Bad Fox looks.

### g:badfox\_darkgutter

Determines whether the line number, sign column, and fold column are rendered
darker than the normal background, or the same.

    " Make the gutters darker than the background.
    let g:badfox_darkgutter = 1

Default: `0` (off, gutters are the same as the background)

### g:badfox\_tabline

Determines how light to render the background of the tab line (the line at the
top of the screen containing the various tabs (only in console mode)).

Can be set to `0`, `1`, `2`, or `3`.

    " Make the tab line darker than the background.
    let g:badfox_tabline = 0

    " Make the tab line the same color as the background.
    let g:badfox_tabline = 1

    " Make the tab line lighter than the background.
    let g:badfox_tabline = 2

    " Make the tab line much lighter than the background.
    let g:badfox_tabline = 3

Default: `1` (same color as the background)

### g:badfox\_html\_link\_underline

Determines whether text inside `a` tags in HTML files will be underlined.

    " Turn off HTML link underlining
    let g:badfox_html_link_underline = 0

Default: `1` (on)

### g:badfox\_css\_props\_highlight

Determines whether CSS properties should be highlighted.

    " Turn on CSS properties highlighting
    let g:badfox_css_props_highlight = 1

Default: `0` (off)

Contributing
------------

I'd love pull requests, but won't necessarily merge all of them.  Color schemes
are a very subjective topic -- we don't all have the same taste.

**If you're going to send a pull request that you want me to merge, please post
a comment in it with before/after screenshots!**
