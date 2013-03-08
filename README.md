This code provide a starting point fo completing assignment 2 in the book IPL.

# Prerequisites

### Haskell

You will need a computer with a recent version ghc with happy and alex. To install haskell
the easyest way is to install the haskell platform (http://www.haskell.org/platform/).

### Make

You will need [GNU Make](http://www.gnu.org/software/make/) to build the code.

- On linux, make is usually available through your distpibution packages, for instances
  - for debian `# apt-get install make`
  - for fedora `#yum install make`
- On mac os x, you need to install XCode
- On windows, you can install make and python as part of [cygwin](http://www.cygwin.com/)

### Python

[Python](http://www.python.org/) is installed by default on most OS. On windows, you can install it
with the [cygwin](http://www.cygwin.com/) installer

# Compiling and testing

To compile the code:

    $ make

To test:

    $ make test

Note that the code should compile without any modifications but it will not pass the test suite!


