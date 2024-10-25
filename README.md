# pn532-hsu-esp32

PN532 HSU(High Speed UART) driver as an ESP-IDF component

## Dependency

- [ESP-IDF](https://github.com/espressif/esp-idf)

## Install

Create a `components` directory in your ESP32 project

```sh
mkdir components
cd components
git clone https://github.com/obe711/pn532-hsu-esp32.git
```

Add this line to the `CMakeLists.txt` in your ESP32 project directory

```
set(EXTRA_COMPONENT_DIRS ./components/pn532-hsu-esp32)
```

## Reference

[Manual](./docs/Manual.pdf)
