csv_parser
==========

[![Build Status](https://travis-ci.org/Alexhuszagh/csv_parser.svg?branch=master)](https://travis-ci.org/Alexhuszagh/csv_parser)
[![Build Status](https://tea-ci.org/api/badges/Alexhuszagh/csv_parser/status.svg)](https://tea-ci.org/Alexhuszagh/csv_parser)
[![Build status](https://ci.appveyor.com/api/projects/status/jx4mmgo25myx9u9i?svg=true)](https://ci.appveyor.com/project/Alexhuszagh/csv_parser)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Alexhuszagh/csv_parser/blob/master/LICENSE.md)

**Table of Contents**

- [Getting Started](#getting-started)
- [Building](#building)
- [Platforms](#platforms)
- [Contributors](#contributors)
- [License](#license)

## Getting Started

## Building

Simply clone, configure with CMake, and build.

```bash
git clone https://github.com/Alexhuszagh/csv_parser.git
git submodule update --init --recursive
cmake .                         # `-DBUILD_TESTS=ON`
make -j 5                       # "msbuild csv_parser.sln" for MSVC
```


## Platforms

crosscxx is continually built with the following compiler and compiler versions:

- MinGW 5.3.0 (MXE, MinGW, and MSYS2) 
- Visual Studio 14 2015
- Visual Studio 15 2017

## Contributors

- Alex Huszagh

## License

The source code is distributed under the [MIT license](LICENSE.md).
