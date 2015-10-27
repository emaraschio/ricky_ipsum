Ricky Ipsum
====

A gem to generate random text based on ["Ricky"](https://es.wikipedia.org/wiki/Ricardo_Fort) phrases.

![Ricardo 'Ricky' Fort](http://www.lacapital.com.ar/__export/1385432919345/sites/core/imagenes/2013/11/26/11-25-es3001--.jpg_88717827.jpg)

Description
-----------

Generate ["Ricky"](https://es.wikipedia.org/wiki/Ricardo_Fort) sentences for filler text while developing anything which requires real text.

Installation
------------

``` console
$ gem install ricky_ipsum
```

Usage
-----

Here's a simple example:

``` ruby
# cat example.rb
require "ricky_ipsum"

# Will print a random phrase
RickyIpsum.text

# Will print four random phrases
RickyIpsum.text(4)

# Will print two random phrases separated by a XHTML BR Tag
RickyIpsum.text(2, "<br />")
```

Thanks
-----

Thanks [yohannaje](https://github.com/yohannaje) for this kind of [inspiration](http://yohannaje.github.io/ricky-ipsum/)

License
-----

All files, unless otherwise noted, are released under the MIT license.

The MIT License (MIT)

Copyright (c) 2015 Ezequiel Maraschio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
