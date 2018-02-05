# CapeLeidokos
A build, development and testing infrastructure for the Kaleidoscope firmware.

<img src="https://github.com/CapeLeidokos/CapeLeidokos/blob/master/CapeLeidokos.svg?sanitize=true">

## Components

[st:stable]: https://img.shields.io/badge/stable-✔-black.svg?style=for-the-badge&colorA=44cc11&colorB=494e52
[st:broken]: https://img.shields.io/badge/broken-X-black.svg?style=for-the-badge&colorA=e05d44&colorB=494e52
[st:experimental]: https://img.shields.io/badge/experimental----black.svg?style=for-the-badge&colorA=dfb317&colorB=494e52

[travis:Leidokos-Python-image]: https://travis-ci.org/CapeLeidokos/Leidokos-Python.svg?branch=master
[travis:Leidokos-Python-status]: https://travis-ci.org/CapeLeidokos/Leidokos-Python

[travis:Leidokos-Testing-image]: https://travis-ci.org/CapeLeidokos/Leidokos-Testing.svg?branch=master
[travis:Leidokos-Testing-status]: https://travis-ci.org/CapeLeidokos/Leidokos-Testing

### [Leidokos-CMake](https://github.com/CapeLeidokos/Leidokos-CMake)

An alternative platform independent build system for [Kaleidoscope](https://github.com/keyboardio/Kaleidoscope).

[Leidokos-CMake:travis:linux:image]: https://img.shields.io/travis/CapeLeidokos/Leidokos-CMake.svg?style=for-the-badge&label=Linux&branch=master
[Leidokos-CMake:travis:linux:target]: https://travis-ci.org/CapeLeidokos/Leidokos-CMake

[Leidokos-CMake:travis:MacOS:image]: https://img.shields.io/travis/CapeLeidokos/Leidokos-CMake.svg?style=for-the-badge&label=Mac&branch=master
[Leidokos-CMake:travis:MacOS:target]: https://travis-ci.org/CapeLeidokos/Leidokos-CMake

[Leidokos-CMake:appveyor:image]: https://img.shields.io/appveyor/ci/CapeLeidokos/Leidokos-CMake/master.svg?style=for-the-badge&label=Windows
[Leidokos-CMake:appveyor:target]: https://ci.appveyor.com/project/CapeLeidokos/Leidokos-CMake/branch/master

[Leidokos-CMake:version:image]: https://img.shields.io/github/release/CapeLeidokos/Leidokos-CMake.svg?style=for-the-badge
[Leidokos-CMake:version:target]: https://github.com/CapeLeidokos/Leidokos-CMake/releases

![status][st:stable]
[![Linux Build Status][Leidokos-CMake:travis:linux:image]][Leidokos-CMake:travis:linux:target]
[![MacOS Build Status][Leidokos-CMake:travis:MacOS:image]][Leidokos-CMake:travis:MacOS:target]
[![Windows Build status][Leidokos-CMake:appveyor:image]][Leidokos-CMake:appveyor:target]
[![Latest version][Leidokos-CMake:version:image]][Leidokos-CMake:version:target]

### [Leidokos-Python](https://github.com/CapeLeidokos/Leidokos-Python)

A Python scriptable [Kaleidoscope](https://github.com/keyboardio/Kaleidoscope) firmware simulator.

[Leidokos-Python:travis:linux:image]: https://img.shields.io/travis/CapeLeidokos/Leidokos-Python.svg?style=for-the-badge&label=Linux&branch=master
[Leidokos-Python:travis:linux:target]: https://travis-ci.org/CapeLeidokos/Leidokos-Python

[Leidokos-Python:travis:MacOS:image]: https://img.shields.io/travis/CapeLeidokos/Leidokos-Python.svg?style=for-the-badge&label=Mac&branch=master
[Leidokos-Python:travis:MacOS:target]: https://travis-ci.org/CapeLeidokos/Leidokos-Python

[Leidokos-Python:version:image]: https://img.shields.io/github/release/CapeLeidokos/Leidokos-Python.svg?style=for-the-badge
[Leidokos-Python:version:target]: https://github.com/CapeLeidokos/Leidokos-Python/releases

[Leidokos-Python:python:api:image]: https://img.shields.io/badge/Python-API-ff69b4.svg?style=for-the-badge
[Leidokos-Python:python:api:target]: https://capeleidokos.github.io/Leidokos-Python/API/index.html

![status][st:stable]
[![Linux Build Status][Leidokos-Python:travis:linux:image]][Leidokos-Python:travis:linux:target]
[![MacOS Build Status][Leidokos-Python:travis:MacOS:image]][Leidokos-Python:travis:MacOS:target]
[![Latest version][Leidokos-Python:version:image]][Leidokos-Python:version:target]

[![Python API documentation][Leidokos-Python:python:api:image]][Leidokos-Python:python:api:target]

### [Leidokos-Testing](https://github.com/CapeLeidokos/Leidokos-Testing)

A regression testing system for the [Kaleidoscope](https://github.com/keyboardio/Kaleidoscope) firmware.

[Leidokos-Testing:travis:linux:image]: https://img.shields.io/travis/CapeLeidokos/Leidokos-Testing.svg?style=for-the-badge&label=Linux&branch=master
[Leidokos-Testing:travis:linux:target]: https://travis-ci.org/CapeLeidokos/Leidokos-Testing

[Leidokos-Testing:version:image]: https://img.shields.io/github/release/CapeLeidokos/Leidokos-Testing.svg?style=for-the-badge
[Leidokos-Testing:version:target]: https://github.com/CapeLeidokos/Leidokos-Testing/releases

![status][st:experimental]
[![Linux Build Status][Leidokos-Testing:travis:linux:image]][Leidokos-Testing:travis:linux:target]
[![Latest version][Leidokos-Testing:version:image]][Leidokos-Testing:version:target]

## Third party dependencies
* [Kaleidoscope](https://github.com/keyboardio/Kaleidoscope)
* [Kaleidoscope-Hardware-Virtual](https://github.com/keyboardio/Kaleidoscope-Hardware-Virtual)
* [Arduino-CMake](https://github.com/CapeLeidokos/arduino-cmake)
