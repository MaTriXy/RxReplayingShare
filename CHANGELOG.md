Change Log
==========

Version 2.0.1 *(2017-09-14)*
----------------------------

 * Fix: Kotlin extension functions now return non-nullable types instead of platform types.


Version 2.0.0 *(2017-07-02)*
----------------------------

This version only supports RxJava 2.

 * New: Support for both `Observable` and `Flowable`.

Note: There is a 2.0.0 version which uses the `com.jakewharton.rx` group ID instead of `com.jakewharton.rx2`.
You should use the latter to ensure 1.x and 2.x can be used side-by-side in the same module.


Version 1.0.1 *(2016-03-31)*
----------------------------

 * Fix: Reduce allocations and memory overhead.


Version 1.0.0 *(2016-03-01)*
----------------------------

Initial release.
