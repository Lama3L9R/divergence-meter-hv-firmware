# Divergence Meter HV Module Firmware

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

DM-HV Module can boost 5V DC input into 154.929V DC - 177.525V DC depend on the switch configuration.

如果需要输入数据为电压值，则编译固件时请编辑文件 `Core/Inc/stm32l0xx_hal_conf.h` 中的宏 `DM_HV_TRANSLATE_MODE` 为 `ON`，反之请修改为 `OFF`。

| Input                     | Output Min    | Output Max    | Max Current | 
|---------------------------|---------------|---------------|-------------|
| `5V DC` And both `3V3 DC` | `154.929V DC` | `177.525V DC` | `350 mA`    |

***すべてが 「Steins Gate」 の選択***

***El Psy Kongroo***
