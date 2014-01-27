box-python-mysqllib
=============

Wercker box for Python with MySQL lib

Source:
https://github.com/shapeup/box-python-mysqllib

use this with wercker; in your wercker.yml file:

``` yaml
services:
  - shapeup/box-python-mysqllib
```


Status on wercker:

[![wercker status](https://app.wercker.com/status/98e3ac5cf12b6e78f1c1770c4d73ebb8/m "wercker status")](https://app.wercker.com/project/bykey/98e3ac5cf12b6e78f1c1770c4d73ebb8)

I've also added a Vagrantfile + provisioning bash script so you can run a local instance with Rethinkdb and test the provisioning

# What's new

- Install MySQL libdev on top of a Python + Ubuntu 12.04 install

# License

The MIT License (MIT)

Copyright (c) 2013 lifesum

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# Changelog

## 0.0.2

- Removed the "packages" instruction see if it helps

## 0.0.1

- Install MySQL libdev on top of a Python + Ubuntu 12.04 install
