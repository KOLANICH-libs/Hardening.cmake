Hardening.cmake
================

Enables various mitigations. Position Independent Code (enables ASLR and is a prereq for sanitizers), DEP (for Windows), various mitigations against microarchitectural vulnrs that destroy performance ... stuff like this.

How to use
----------

1. Add this repo as a submodule into your repo.
2. Point CMake to search for modules in it.
3. `include(Hardening)`
4. `harden(<your target>)`
