# CANopen

Project is meant for use in mbed OS, e.g low-level Arduino.
Forked from https://github.com/curvi/CANopen

It is a simple generic library, with all unnecessary dependencies removed, so you don't need to use a specific driver, just pass a mbed::CAN-compatible driver to `void CANopen::setup(mbed::CAN &can_interface)`

---
- Tested with Portenta H7 lite
- TODO: will add example usage
