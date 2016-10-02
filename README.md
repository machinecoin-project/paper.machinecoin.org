# paper.machinecoin.org
JavaScript Client-Side Machinecoin Wallet Generator

Now Machinecoin addresses and their corresponding private key can be conveniently 
generated in a web browser.

The paper.machinecoin.org project provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the 
JavaScript locally and trust that the JavaScript did not change after being 
loaded. 


Please send DONATIONS for this project to Machinecoin Address: 
MDSQf1PSdrpTBE8GGV4ydhAqq9z5AbMDAw


END USER NOTES:

 1) To print QRCode in IE8 you must enable the "Print Background Colors and 
    Images" checkbox on the "Page Setup" screen.

 2) For Bulk Wallet I recommended using Google Chrome, it's the fastest.

 3) Requires IE8+, Firefox, Chrome or sufficient JavaScript support.

 4) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.

 5) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.

 6) Art Wallet does not work properly in IE8 due to CSS limitations.


Notice of Copyrights and Licenses:
---------------------------------------
The paper.machinecoin.org project, software and embedded resources are
copyright paper.machinecoin.org.

Portions of the all-in-one HTML document contain JavaScript codes and fonts that
are the copyrights of others. The individual copyrights are included
throughout the document along with their licenses. Included JavaScript
libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

JavaScript function	|	License
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

Summary of fonts with a non-commercial license:

Font	|	License
-------------------	|	--------------
FHA Condensed French NC	|	http://thefontry.com/fhacondensedfrench

The paper.machinecoin.org software is available under The MIT License (MIT)
Copyright (c) 2011-2013 bitaddress.org
Copyright (c) 2014-2016 paper.machinecoin.org

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
