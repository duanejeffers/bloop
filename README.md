bloop
=====

Copyright (c) 2012 Duane Jeffers <duanejeffers.com>
Based on blorpscript by Justin Frankel <1014.org>

License
----
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

What is this thing?
----
bloop is the object oriented blorpscript. It's meant to be a gallery generation tool, updated to include 5.3 coding concepts. No more requirements for register_globals (security issue) and integrated an administration panel.

Why ...?
----
Because HTML5 gallery generation and the ability to manipulate the output through OOP MVC concepts. There is a plugin API and handler for developing with the system. Want to build a CMS? You can with bloop.

Sure ... But Why a flat file?
----
Flat files are cool. It only requires one file to download and it works.

How can I add (some extension of a filetype here)?
----
The bloopViewExt class can be extended and then added to the view plugins folder. It just works!