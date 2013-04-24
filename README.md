Whitespace
==========
Whitespace is a minimal and responsive theme for [Octopress](http://octopress.org). This theme let your contents take the center stage of your blog.

Check out the theme in action [here](http://lucaslew.com).


Install
-------
    $ cd octopress
    $ git clone git://github.com/lucaslew/whitespace.git .themes/whitespace
    $ rake install['whitespace']
    $ rake generate


HTML Elements Changes
---------------------
Changes that apply to blog content(article)

	h3 - presented in italic
	a, a:visited - blue color as default
	ul, ol - left margin of 2em

If you spot any error, feel free to send me suggestions to improve. Thanks!


Comment System
--------------
Added support for open-source [Juvia](https://github.com/phusion/juvia) comment system. It requires two extra parameters in _config.yml: `juvia_site_key` and `juvia_host`.


License
-------
(The MIT License)

Copyright © 2013 Lucas Lew

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


