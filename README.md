Whitespace
==========
Whitespace is a minimal and responsive theme for [Octopress](http://octopress.org). This theme lets your contents take the center stage of your blog.


Demos
-----

Unmodified: [Lucas Lew's blog](http://lucaslew.com).

Slightly customized: [Chymeric Tutorials](http://chymeric.eu), [Yous' Blog](http://yous.be/)

*If you are using whitespace and would like to showcase your website, we would be very happy to add you to the list! Just tell us your URL via the issue tracking system!*


Install
-------
    $ cd octopress
    $ git clone git://github.com/lucaslew/whitespace.git .themes/whitespace
    $ rake install['whitespace']
    $ rake generate


Update
------
    $ cd octopress/.themes/whitespace
    $ git pull
    $ rake install['whitespace']
    $ rake generate


Update and Keep Customizations
------------------------------
*For this to work, you have to track your website theme customizations on a remote (we call it ```mywebsiterepo```).*

    $ cd octopress/.themes/whitespace
    $ git pull
    $ rake install['whitespace']
    $ cd ../..
    $ git fetch --all
    $ git reset --hard mywebsiterepo/master
    $ rake generate


Comment System
--------------
Added support for open-source [Juvia](https://github.com/phusion/juvia) comment system. It requires two extra parameters in `_config.yml`: `juvia_site_key` and `juvia_host`.


Navigation Bar
--------------
You can add several icons to the navigation bar. Just set some parameters in `_config.yml`:

- `googleplus_user` with `googleplus_hidden: false` for Google+ profile.
- `pinboard_user` for Pinboard bookmarks.
- `delicious_user` for Delicious bookmarks.
- `github_user` with `github_show_profile_link: true` for GitHub profile.
- `bitbucket_user` for Bitbucket profile.


External URL
------------
You can write a [Linklog](http://en.wikipedia.org/wiki/Linklog) by using this theme. To publish a linked post, just add `external-url` variable in the YAML front matter of your post.

    ---
    layout: post
    ...
    external-url: http://example.com/some/external/url
    ---

Then the title will have '&rarr;' at the end. Also the title link will point to the external url.

Google+ authored by link
------------------------
By default posts will contain a link with `rel="author"` to the Google+ profile if the `googleplus_user` variable is set in `_config.yml`.

You can override the pofile for the authored by link for a specific post by adding `googleplus_user` for the post:  

    ---
    layout: post
    ...
    gooleplus_user: [put overriding profile id here]
    ---
	
You can also choose to ignore the link by specifying `ignore` for `googleplus_user` for the post. The authored by text will then be displayed without a link.

    ---
    layout: post
    ...
    gooleplus_user: ignore
    ---

License
-------
(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


