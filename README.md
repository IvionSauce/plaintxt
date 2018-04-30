# About
This a theme for Pelican-powered blogs, based on the [veryplaintxt theme](http://www.plaintxt.org/#veryplaintxt) (originally made for Wordpress-powered blogs).

# Requirements
Obviously this requires Pelican, but this theme also makes use of the [tag-cloud plugin](https://github.com/getpelican/pelican-plugins/tree/master/tag_cloud). Only 4 tag-cloud steps are actually themed, so any more than that will cause issues.

# Gotcha’s
It is is strongly recommended to use only `h3`–`h6` in the articles you write, otherwise you break both the structure of the HTML page and the themeing (since I don’t take `h1` and `h2` inside articles into account). The title of the website is `h1` and the title of the post/blog entry is `h2`, hence only `h3` and below are available for the division of post contents. Following this will ensure the resultant HTML documents are semantically structured.

# Copyright and stuff
This project is licensed under the _GNU Lesser General Public License_ version 3, which is the license the original theme was released under. I have included the original theme as `veryplaintxt.zip` for those interested (or you could visit [the website](http://www.plaintxt.org/#veryplaintxt)).
