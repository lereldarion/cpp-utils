Duck cpp utils library
===============================

[![Build Status](https://travis-ci.org/lereldarion/duck.svg?branch=master)](https://travis-ci.org/lereldarion/duck)
[![Duck License](https://img.shields.io/github/license/mashape/apistatus.svg)]()

Small collections of C++14 header only useful classes.
Currently under namespace `duck`.

Setup
-----

Header only, so no compilation is required.
A standard cmake setup is provided, which can compile and launch some tests, and create cmake package files.

Status
------

Currently completely work in progress.
TODO:
- add license stuff and small doc in files.
- add nocompile tests for range
- add test for integer range
- expand std::algorithm version with ranges ? no tests though. keep wrapper namespace ?
- add combinators (range expressions)
- split range in basic mode (no fancy apply stuff), and a full featured range

License
-------

```
MIT License

Copyright (c) 2016-2017 Francois Gindraud

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```