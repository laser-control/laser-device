# Device
The goal of the project is to be able to drive this device from a computer.

A lot of similar devices can be [found on sale](https://de.aliexpress.com/w/wholesale-laser-show-system.html?spm=a2g0o.home.auto_suggest.2.269a7a8b2kO67i)

## TODO

1. develop a protocol between the device and computer
2. implement the software to run on chip (with the doc how to compile, install and run on chip)
3. implement hardware using STM32 blue pill (STM32F103C6**)

The protocol may be as simple as possible to parse and run on chip.
(it does not have to be complex G-code)

There is also [DMX interface](DMX.md), but I am not sure if it works

## Hardware

### Motors

1. The device has two [unipolar step motors.](step-motors.md)

### Internals
![View](docs/images/Laser-device-view-1.png)

[This is how](https://youtube.com/shorts/rjiIK6qfQHM?feature=share)
the device begins to work.


#### View
![photo11](docs/images/Device-open-1.jpg)
![photo12](docs/images/Device-open-2.jpg)
![photo13](docs/images/Device-open-3.jpg)
![photo14](docs/images/Device-control-board-1.jpg)
![photo15](docs/images/Device-open-back-1.jpg)

#### Mirrors
![photo24](docs/images/Device-mirrors-1.jpg)
![photo25](docs/images/Device-mirrors-2.jpg)
