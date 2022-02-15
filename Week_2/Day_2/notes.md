# Week 2 - Day 2 - Lecture

> Computing can be boiled down to 3 things. Input, Processing, Outputs

Main thread 

**Event loop - event loop does not start until the main thread has finished**

* use the next function you want to run as a parameter to set up a sequence.

* you set a bunch of stuff up for the event loop

* a scheduled function can not return values, they can only side effect

* the event loop itself calls the functions
  * you have to call a function to do things after the main thread has finished

* 'fs' is the file system built into node

* 