# hpp-manipulation-urdf

[![Building Status](https://travis-ci.org/humanoid-path-planner/hpp-manipulation-urdf.svg?branch=master)](https://travis-ci.org/humanoid-path-planner/hpp-manipulation-urdf)
[![Pipeline status](https://gepgitlab.laas.fr/humanoid-path-planner/hpp-manipulation-urdf/badges/master/pipeline.svg)](https://gepgitlab.laas.fr/humanoid-path-planner/hpp-manipulation-urdf/commits/master)
[![Coverage report](https://gepgitlab.laas.fr/humanoid-path-planner/hpp-manipulation-urdf/badges/master/coverage.svg?job=doc-coverage)](http://projects.laas.fr/gepetto/doc/humanoid-path-planner/hpp-manipulation-urdf/master/coverage/)

This package is part of the [HPP] software and extends the functionalities of hpp-model-urdf.
It implements a URDF/SRDF parser for the package hpp-manipulation.

### Version
1.1

### Dependencies

hpp-manipulation-urdf needs the following package to be installed:

* [hpp-manipulation]
* [hpp-model]
* [hpp-util]
* [ressource_retriever] is a ROS package.
* [hpp-model-urdf] is a URDF/SRDF parser for [HPP] software.
* [TinyXML] is a simple, small, efficient, C++ XML parser.

### Installation

Make sure you have installed all the dependency.

```sh
$ git clone https://github.com/billx09/hpp-manipulation-urdf
$ cd hpp-manipulation-urdf
$ mkdir build && cd build
$ cmake ..
$ make install
```

### Todo's

* Implement a factory for AxialHandle (See [hpp-manipulation])

[TinyXML]:http://www.grinninglizard.com/tinyxml
[hpp-model-urdf]:https://github.com/humanoid-path-planner/hpp-model-urdf
[HPP]:https://github.com/humanoid-path-planner/hpp-doc
[hpp-manipulation-urdf]:https://github.com/billx09/hpp-manipulation-urdf
[hpp-manipulation]:https://github.com/billx09/hpp-manipulation
[hpp-model]:https://github.com/humanoid-path-planner/hpp-model
[hpp-util]:https://github.com/humanoid-path-planner/hpp-util
[ressource_retriever]:http://wiki.ros.org/resource_retriever
