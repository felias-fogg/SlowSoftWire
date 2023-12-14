# SlowSoftWire

A wrapper for SlowSoftI2CMaster emulating the functionality of the Wire library (for master clients). In order to use it, you also have to download [SlowSoftI2CMaster](https://github.com/felias-fogg/SlowSoftI2CMaster).

This has been derived from the Arduino Wire library and is published
under the same license: the [LGPL](http://www.gnu.org/licenses/lgpl-3.0.html). 

### New library

This library has been archived! Please use the new [FlexWire](https://github.com/felias-fogg/FlexWire) library instead. It is based on SlowSoftWire, fixes one bug, can act as a drop-in replacement for Wire (see my [blog post on it](https://arduino-craft-corner.de/index.php/2023/11/29/replacing-the-wire-library-sometimes/)), and has a new method called `setPins`, which can be used to change the pin assignment for the I2C bus dynamically, thereby supporting a kind of [software I2C multiplexing](https://arduino-craft-corner.de/index.php/2023/12/14/software-i2c-multiplexer/).
