RSA Timing attack implementation with Montgomery Product and Powering Ladder
===========================================================================

We implement a timing attack on the RSA algorithm, to recover the private key.
We then implement RSA using Montgomery Powering Ladder as a countermeasure, and show that the timing attack now is ineffective.

Building and running
-------------------

```
$ cd build
$ cmake .. && make
$ ./rsa
```

Requires cmake, make, c++11 compiler.
