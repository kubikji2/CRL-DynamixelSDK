# Dynamixel SDK Release Notes

## 1.0.0 (2024-05-14)

* Branched of the 3.7.51 in original repo
* Focusing only to the C implementation in legacy format, I do not wanna waste time fixing the legacy code.
* Fixing the `port_handler_linux` such that the default value for baudrate (baudbase) compatible with the in-house designed UART to USB with zero baudbase set.
