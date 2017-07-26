## Infix operators for numpy arrays

Originally published: 2010-04-19 05:20:50
Last updated: 2010-06-07 05:57:07
Author: John Schulman

This recipe adapts the infix operator trick from http://code.activestate.com/recipes/384122-infix-operators/ to give the appropriate behavior with numpy arrays, so you can write A \\*dot\\* B for np.dot(A,B)