# bison++ version 1.21-8 patched

This is a way to generate a parser class. Usually bison or yacc is used. But with bison++ you can have a parser c++ class.
Found the latest version I could find on the internet and it didn't compile anymore on my macOS big sur. Patched the errors
so it compiles and installs again.

# Installation

```
brew install make flex
./configure
make
make install
```

If all goes well you should now have a working bison++ binary and by running make install it's installed in /usr/local/bin
For an example on how to use this go to http://walter.schreppers.com/archive/115


