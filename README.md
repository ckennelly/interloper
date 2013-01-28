interloper - An On-The-Fly Library Interposition Utility
(c) 2013 - Chris Kennelly (chris@ckennelly.com)

Overview
========

`interloper` runs an executable and provides on-the-fly interposition capabilities.  As external symbol dependencies are encountered, a stub is created to proxy calls to the appropriate shared library.  These stubs can be subsequently modified to perform library interposition at runtime without iterating between editing, compiling, running a prototype.

Debugging symbols are heavily relied upon.
