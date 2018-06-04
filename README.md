# plaintxt, a Pelican theme

## About
This a theme for [Pelican](https://blog.getpelican.com/)-powered blogs, based on the [veryplaintxt theme](http://www.plaintxt.org/#veryplaintxt) (which was made for Wordpress-powered blogs).

## Requirements
Obviously this requires Pelican, but this theme’s templates also make use of the [tag-cloud plugin](https://github.com/getpelican/pelican-plugins/tree/master/tag_cloud).

## Gotchas
It is strongly recommended to only use `h3`–`h6` in the articles you write, otherwise you break both the structure of the HTML page and the themeing (since I don’t take `h1` and `h2` inside articles into account). The title of the website is `h1` and the title of the post/blog entry is `h2`, hence only `h3` and below are available for the division of post contents. Following this will ensure the resultant HTML documents are semantically structured.

Only 4 tag-cloud steps are actually themed, so any more steps will cause style issues.

## Copyright and stuff
This theme – with the exception of the included fonts and background patterns – is licensed under the _GNU Lesser General Public License_ version 3, which is the license the original theme was released under. I have included the original theme as `veryplaintxt.zip` for those interested (or you could visit [the website](http://www.plaintxt.org/#veryplaintxt)).

### Fonts
The EB Garamond and Playfair Display fonts are licensed under the _SIL Open Font License_ version 1.1; it is included as `fonts.license`. [EB Garamond](http://www.georgduffner.at/ebgaramond/) is made by Georg Duffner, and [Playfair Display](https://github.com/clauseggers/Playfair-Display) is made by Claus Eggers Sørensen.

### Background patterns
The background patterns Blizzard, Debut Light, Groovepaper and Subtle White Feathers are from [Toptal Subtle Patterns](https://www.toptal.com/designers/subtlepatterns/). They are licensed under the _Creative Commons Attribution-ShareAlike 3.0 Unported_ ([CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)) license; it is included as `backgrounds.license`.
- [Blizzard](https://www.toptal.com/designers/subtlepatterns/blizzard/)
- [Debut Light](https://www.toptal.com/designers/subtlepatterns/debut-light/)
- [Groovepaper](https://www.toptal.com/designers/subtlepatterns/groovepaper/)
- [Subtle White Feathers](https://www.toptal.com/designers/subtlepatterns/subtle-white-feathers/)
