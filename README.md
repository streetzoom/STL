# STL

A Palindrome is a string that reads the same backwards or forwards.

Simple examples are:
madam
bob
toot
radar

===================================================================

An entire phrase can also be a palindome, for example:

A Toyota's a toyota

A Santa at NASA

A man, a plan, a cat, a ham, a yak, a yam, a hat, a canal-Panama!

===================================================================


For the purposes of this assignment we will only consider alpha characters and omit all other characters.

We will also not be considering case.

So,
A Santa at Nasa, will be processed as:
ASANTAATNASA

===================================================================

A common method to solve this problem is to compare the string to its reverse and
if the are equal then it must be a palindrome. But we will use a deque.

So,

is_palindrome("A Santa at Nasa");   will return true 

is_palindrome("Hello");   will return false

Please use a deque to solve the problem.



