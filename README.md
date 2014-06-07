Whitespace
==========
Whitespace is a minimal and responsive theme for [Octopress](http://octopress.org). This theme lets your contents take the center stage of your blog.


Demos
-----

Unmodified: [Lucas Lew's blog](http://lucaslew.com).

Slightly customized: [Chymeric Tutorials](http://tutorials.chymera.eu)

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


Comment System
--------------
Added support for open-source [Juvia](https://github.com/phusion/juvia) comment system. It requires two extra parameters in _config.yml: `juvia_site_key` and `juvia_host`.


License
-------
(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


