Just a basic template project using CMake and Conan.IO, to act as a starting point for
a project using Conan.IO, and Boost at it's core.

Conan.io in the respective environment will have to be installed.

Then, the libraries installed, and the project built, with:

```
# conan install .
# cmake .
# make
```

Then add . to DYLD_LIBRARY_PATH:

```
# export DYLD_LIBRARY_PATH=$DYLD_LIBRARY_PATH:.
```

Go into the bin directory and run the produced binary:
```
cd bin/
./conanboosttemplate
```

