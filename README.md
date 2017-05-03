Slow, limited vocabulary audio drills
=====================================

How-to
------

	node main.js [1-80]

The argument specifies how many hundreds of words of vocabulary to use in the
drill. You will hear sentences that contain only the top arg×100 words.

To adjust the speed, edit the formula in ``main.js`` inside the "repeat" perens.

To adjust the length, edit ``g_min_length`` in ``main.js``


Notes
-----

Each sentence in a given drill will contain at least one word from the last
(least used) 100 words of the vocabulary set.

Sentences were extracted by an algorithm from an arbitrary collection of books
from Project Gutenberg.


License
-------

See LICENSE.txt
