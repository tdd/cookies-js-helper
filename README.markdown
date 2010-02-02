Small Cookies JavaScript Helper
===============================

#### Tweaking cookies in a snap, nothing else required ####

This is a tiny bit of robust JavaScript functionality that lets you tweak cookies
from within your web page in very little code, without needing any other library.
It does not clash with any major JS framework, although it does share a namespace
with MooTool’s Cookie utility.

### Targeted platforms ###

This code has been tested on the following browsers:

* Microsoft Internet Explorer for Windows, version 6.0 and higher
* Mozilla Firefox 1.5 and higher
* Apple Safari 2.0.4 and higher
* Opera 9.25 and higher
* Chrome 1.0 and higher

Using this helper
-----------------

Download the latest release from the repository (<http://github.com/tdd/cookies-js-helper>)
and copy `src/cookies.js` to a suitable location. Then include it in your HTML like so:

    <script type="text/javascript" src="/path/to/cookies.js"></script>

Documentation
-------------

The code is fairly straightforward, there are basically five methods in the `Cookie`
namespace: `get`, `set`, `remove`, `list` and `test`.

For full details, look at the inline documentation before each method body.

Feedback
--------

Feedback is encouraged through GitHub comments and tickets!

Cheers,

Christophe Porteneuve