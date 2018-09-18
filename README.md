![adaptive-logo](./doc/adaptive.jpeg)

adaptiv:: is an MDO framework targeted primarily at the aerospace industry. It is written in C++ and the main design driver is *efficiency*. *Modularity* and *extensibility* are also important attributes to realize the goal of providing standalone multiphysics and optimization libraries as well as an engine for their integration.

```cpp
#include "adp/fluid.h"
#include "adp/solid.h"
#include "adp/accoustics.h"
```

## References & guides

1. Git cheat sheet for quick reference of commonly used command line instructions

2. C++ book guide (WIP)
    * **Bigginer introduction**
        1. [Programming: Principles and Practice Using C++](https://www.amazon.com/dp/0321992784/)
    * **Standard Template Library**
        1. Containers
        2. Iterators
        3. Algorithms
3. Google C++ testing framework

## Planning

1. Core math library
    * MKL and/or cuBLAS wrapper
    * Check implementations of current math libraries (_e.g._  [Eigen](http://eigen.tuxfamily.org))
    * N-dimentional arrays:
        * [A Class Template for N-Dimensional Generic Resizable Arrays](http://www.drdobbs.com/a-class-template-for-n-dimensional-gener/184401319)
        * [LibFlatArray](http://www.libgeodecomp.org/libflatarray.html)
##

<p align="right">
    <a ref="https://tecnico.ulisboa.pt/en/">
    <img src="./doc/IST_logo.png" height="100" alt="IST-logo" align="right" >
</p>