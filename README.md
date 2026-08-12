# Autodesk Eagle Library

Autodesk Eagle component library (`common components.lbr`) plus design rules (`DesignRules.dru`).

## Library summary

| Type | Count |
|------|------:|
| Components (devicesets) | 48 |
| Symbols | 58 |
| Footprints (packages) | 113 |
| Device variants | 126 |

## Components by category

| Category | Components | Variants |
|----------|----------:|---------:|
| Resistors | 1 | 6 |
| Capacitors | 2 | 42 |
| Transistors | 4 | 5 |
| MOSFETs | 2 | 4 |
| Diodes | 1 | 1 |
| LEDs | 2 | 4 |
| ICs | 4 | 5 |
| Relays | 1 | 1 |
| Modules / Boards | 10 | 14 |
| Connectors / Terminal Blocks | 9 | 11 |
| Switches | 2 | 14 |
| Batteries / Holders | 3 | 3 |
| Transformers | 1 | 1 |
| Supply / Power Symbols | 4 | 4 |
| Mechanical / Mounting | 1 | 10 |
| Documentation / Drawing | 1 | 1 |
| **Total** | **48** | **126** |

### Resistors (1)

| # | Component | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-----------|--------------|---------:|
| 1 | `RESISTOR` | `R-EU` | `0207/10`, `0207/12`, `0207/15`, `R0603`, `R0805`, `R1206` | 6 |

### Capacitors (2)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `C-EU` | Non-polarized | `C-EU` | `C025-025X050`, `C050-025X075`, `C0603K`, `C0805K`, `C1206K` | 5 |
| 2 | `CPOL-EU` | Polarized | `CPOL-EU` | CT*, E*, Panasonic*, SMC*, D/7343* (37 pkgs) | 37 |

### Transistors (4)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `2N3904` | NPN | `NPN-3` | `TO92` | 1 |
| 2 | `BC547*` | NPN | `NPN-1` | `TO92` | 1 |
| 3 | `BC807*` | PNP | `PNP` | `SOT23-BEC`, `SOT323-BEC` | 2 |
| 4 | `BC817*` | NPN | `NPN-2` | `SOT23-BEC` | 1 |

### MOSFETs (2)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `IRF540` | N-ch 100V 28A | `IGFET-EN-GDS` | `TO220`, `TO220BV` | 2 |
| 2 | `IRF9540` | P-ch −100V −12A | `IGFET-EP-GDS` | `TO220`, `TO220BV` | 2 |

### Diodes (1)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `1N581*` | Schottky barrier rectifier 1.0A | `SCHOTTKY` | `DO41-7.6` | 1 |

### LEDs (2)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `LED` | Standard LED | `LED` | `CHIP-LED0603`, `LED3MM`, `LED5MM` | 3 |
| 2 | `WS2812B` | Addressable RGB | `LED-TRICOLOR-WS28X1` | `WS2812B` | 1 |

### ICs (4)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `4047` | Monostable/astable multivibrator | `4047`, `PWRN` | `DIL14`, `SO14` | 2 |
| 2 | `IR2104` | Half-bridge driver | `IR2104` | `SO08` | 1 |
| 3 | `MCP41010` | Digital potentiometer | `MCP41010` | `SO08` | 1 |
| 4 | `PCA9685` | 16-ch PWM controller | `PCA9685` | `TSSOP28` | 1 |

### Relays (1)

| # | Component | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-----------|--------------|---------:|
| 1 | `AQG22205` | `AQG22205` | `AQG22205` | 1 |

### Modules / Boards (10)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `ARDUINO2009_1` | Arduino Duemilanove | `ARDUINO2009` | `ARDUINO2009`, `ARDUINO2009_1`, `ARDUINO2009_2` | 3 |
| 2 | `MEGAARDUINO_1` | Arduino Mega | `MEGAARDUINO_1` | `MEGA_ARDUINO`, `MEGA_ARDUINO_1`, `MEGA_ARDUINO_2` | 3 |
| 3 | `ESP32-CAM` | ESP32 camera module | `ESP32-CAM` | `ESP32-CAM` | 1 |
| 4 | `ESP32-DEVKITV1` | ESP32 DevKit | `ESP32-DEVKITV1` | `ESP32-DEVKITV1` | 1 |
| 5 | `DRV8833_MODULE` | Motor driver module | `DRV8833_MODULE` | `DRV8833_MODULE` | 1 |
| 6 | `LM2596-NO_DISPLAY` | Buck converter module | `LM2596-NO_DISPLAY` | `LM2596-NO_DISPLAY` | 1 |
| 7 | `XL6019` | Boost converter module | `XL6019` | `XL6019` | 1 |
| 8 | `OLED_0.96_I2C` | 0.96" OLED I2C | `OLED_0.96_I2C` | `OLED_0.96_I2C` | 1 |
| 9 | `OLED_0.96_SPI_SERIAL` | 0.96" OLED SPI | `OLED_9.96_SPI_SERIAL` | `OLED_9.96_SPI_SERIAL` | 1 |
| 10 | `PWM-SERVO-DRIVER-16CH` | 16-ch PWM/servo board | `PWM-SERVO-DRIVER-16CH` | `PWM-SERVO-DRIVER-16CH` | 1 |

### Connectors / Terminal Blocks (9)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `CONN_03` | 3-pin header | `CONN_03` | `1X03`, `1X03_LONGPADS` | 2 |
| 2 | `CONN_04` | 4-pin header | `CONN_04` | `1X04`, `1X04_LONGPADS` | 2 |
| 3 | `MKDSN1,5/2-5,08` | Terminal 2-pin | `KLV` | `MKDSN1,5/2-5,08` | 1 |
| 4 | `MKDSN1,5/3-5,08` | Terminal 3-pin | `KL`, `KLV-1` | `MKDSN1,5/3-5,08` | 1 |
| 5 | `MKDSN1,5/4-5,08` | Terminal 4-pin | `KL-1`, `KLV-2` | `MKDSN1,5/4-5,08` | 1 |
| 6 | `MKDSN1,5/5-5,08` | Terminal 5-pin | `KL-2`, `KLV-3` | `MKDSN1,5/5-5,08` | 1 |
| 7 | `MKDSN1,5/6-5,08` | Terminal 6-pin | `KL-3`, `KLV-4` | `MKDSN1,5/6-5,08` | 1 |
| 8 | `MKDSN1,5/7-5,08` | Terminal 7-pin | `KL-4`, `KLV-5` | `MKDSN1,5/7-5,08` | 1 |
| 9 | `MKDSN1,5/8-5,08` | Terminal 8-pin | `KL-5`, `KLV-6` | `MKDSN1,5/8-5,08` | 1 |

### Switches (2)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `MOMENTARY-SWITCH-SPST` | Pushbutton SPST | `SWITCH-MOMENTARY-2` | 11 tactile packages | 12 |
| 2 | `MOMENTARY-SWITCH-SPST-2` | Pushbutton SPST 2-circuit | `SWITCH-MOMENTARY` | `TACTILE_SWITCH_SMD_4.6X2.8MM`, `TACTILE_SWITCH_SMD_5.2MM` | 2 |

### Batteries / Holders (3)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `BATTERY-HOLDER-2AA` | 2×AA holder | `BATTERY-HOLDER-2AA` | `BATTERY-HOLDER-2AA` | 1 |
| 2 | `BATTERY-HOLDER-2AAA` | 2×AAA holder | `BATTERY-HOLDER-2AAA` | `BATTERY-HOLDER-2AAA` | 1 |
| 3 | `BATTERY-LI-MH12210` | Li-ion cell | `BATTERY-LI-MH12210` | `BATTERY-LI-MH12210` | 1 |

### Transformers (1)

| # | Component | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-----------|--------------|---------:|
| 1 | `EF20` | `TRAFO_EF20_180:60:60` | `EF-TRANSFORMER` | 1 |

### Supply / Power Symbols (4)

| # | Component | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-----------|--------------|---------:|
| 1 | `+12V` | `+12V` | — | 1 |
| 2 | `+24V` | `+24V` | — | 1 |
| 3 | `GND` | `SUPPLY1_GND` | — | 1 |
| 4 | `VCC` | `SUPPLY1_VCC` | — | 1 |

### Mechanical / Mounting (1)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `MOUNT-PAD-ROUND` | Round mounting pad | `MOUNT-PAD` | `2,8-PAD` … `5,5-PAD` (10 sizes) | 10 |

### Documentation / Drawing (1)

| # | Component | Description | Symbol(s) | Footprint(s) | Variants |
|--:|-----------|-------------|-----------|--------------|---------:|
| 1 | `A4L-LOC` | DIN A4 landscape frame | `A4L-LOC` | — | 1 |

## Symbols (58)

| # | Symbol | # | Symbol |
|--:|--------|--:|--------|
| 1 | `+12V` | 30 | `KLV-4` |
| 2 | `+24V` | 31 | `KLV-5` |
| 3 | `4047` | 32 | `KLV-6` |
| 4 | `A4L-LOC` | 33 | `LED` |
| 5 | `AQG22205` | 34 | `LED-TRICOLOR-WS28X1` |
| 6 | `ARDUINO2009` | 35 | `LM2596-NO_DISPLAY` |
| 7 | `BATTERY-HOLDER-2AA` | 36 | `MCP41010` |
| 8 | `BATTERY-HOLDER-2AAA` | 37 | `MEGAARDUINO_1` |
| 9 | `BATTERY-LI-MH12210` | 38 | `MFN` |
| 10 | `C-EU` | 39 | `MFP` |
| 11 | `CONN_03` | 40 | `MOUNT-PAD` |
| 12 | `CONN_04` | 41 | `NPN` |
| 13 | `CPOL-EU` | 42 | `NPN-1` |
| 14 | `DRV8833_MODULE` | 43 | `NPN-2` |
| 15 | `ESP32-CAM` | 44 | `NPN-3` |
| 16 | `ESP32-DEVKITV1` | 45 | `OLED_0.96_I2C` |
| 17 | `IGFET-EN-GDS` | 46 | `OLED_9.96_SPI_SERIAL` |
| 18 | `IGFET-EP-GDS` | 47 | `PCA9685` |
| 19 | `IR2104` | 48 | `PNP` |
| 20 | `KL` | 49 | `PWM-SERVO-DRIVER-16CH` |
| 21 | `KL-1` | 50 | `PWRN` |
| 22 | `KL-2` | 51 | `R-EU` |
| 23 | `KL-3` | 52 | `SCHOTTKY` |
| 24 | `KL-4` | 53 | `SUPPLY1_GND` |
| 25 | `KL-5` | 54 | `SUPPLY1_VCC` |
| 26 | `KLV` | 55 | `SWITCH-MOMENTARY` |
| 27 | `KLV-1` | 56 | `SWITCH-MOMENTARY-2` |
| 28 | `KLV-2` | 57 | `TRAFO_EF20_180:60:60` |
| 29 | `KLV-3` | 58 | `XL6019` |

## Footprints (113)

| # | Footprint | # | Footprint |
|--:|-----------|--:|-----------|
| 1 | `0207/10` | 58 | `ESP32-CAM` |
| 2 | `0207/12` | 59 | `ESP32-DEVKITV1` |
| 3 | `0207/15` | 60 | `LED3MM` |
| 4 | `1X03` | 61 | `LED5MM` |
| 5 | `1X03_LONGPADS` | 62 | `LM2596-NO_DISPLAY` |
| 6 | `1X04` | 63 | `MEGA_ARDUINO` |
| 7 | `1X04_LONGPADS` | 64 | `MEGA_ARDUINO_1` |
| 8 | `2,8-PAD` | 65 | `MEGA_ARDUINO_2` |
| 9 | `3,0-PAD` | 66 | `MKDSN1,5/2-5,08` |
| 10 | `3,2-PAD` | 67 | `MKDSN1,5/3-5,08` |
| 11 | `3,3-PAD` | 68 | `MKDSN1,5/4-5,08` |
| 12 | `3,6-PAD` | 69 | `MKDSN1,5/5-5,08` |
| 13 | `4,1-PAD` | 70 | `MKDSN1,5/6-5,08` |
| 14 | `4,3-PAD` | 71 | `MKDSN1,5/7-5,08` |
| 15 | `4,5-PAD` | 72 | `MKDSN1,5/8-5,08` |
| 16 | `5,0-PAD` | 73 | `OLED_0.96_I2C` |
| 17 | `5,5-PAD` | 74 | `OLED_9.96_SPI_SERIAL` |
| 18 | `AQG22205` | 75 | `PANASONIC_A` |
| 19 | `ARDUINO2009` | 76 | `PANASONIC_B` |
| 20 | `ARDUINO2009_1` | 77 | `PANASONIC_C` |
| 21 | `ARDUINO2009_2` | 78 | `PANASONIC_D` |
| 22 | `BATTERY-HOLDER-2AA` | 79 | `PANASONIC_E` |
| 23 | `BATTERY-HOLDER-2AAA` | 80 | `PANASONIC_F` |
| 24 | `BATTERY-LI-MH12210` | 81 | `PANASONIC_G` |
| 25 | `C025-025X050` | 82 | `PWM-SERVO-DRIVER-16CH` |
| 26 | `C050-025X075` | 83 | `R0603` |
| 27 | `C0603K` | 84 | `R0805` |
| 28 | `C0805K` | 85 | `R1206` |
| 29 | `C1206K` | 86 | `SMC_A` |
| 30 | `CHIP-LED0603` | 87 | `SMC_B` |
| 31 | `CT3216` | 88 | `SMC_C` |
| 32 | `CT3528` | 89 | `SMC_D` |
| 33 | `CT6032` | 90 | `SMC_E` |
| 34 | `CT7343` | 91 | `SMC_P` |
| 35 | `D/7343-31R` | 92 | `SMC_Z` |
| 36 | `D/7343-31W` | 93 | `SO08` |
| 37 | `DIL14` | 94 | `SO14` |
| 38 | `DO41-7.6` | 95 | `SOT23-BEC` |
| 39 | `DRV8833_MODULE` | 96 | `SOT323-BEC` |
| 40 | `E1,8-4` | 97 | `TACTILE_SWITCH_PTH_12MM` |
| 41 | `E2,5-5` | 98 | `TACTILE_SWITCH_PTH_6.0MM` |
| 42 | `E2,5-6` | 99 | `TACTILE_SWITCH_PTH_6.0MM_KIT` |
| 43 | `E2,5-6E` | 100 | `TACTILE_SWITCH_PTH_RIGHT_ANGLE_KIT` |
| 44 | `E2,5-7` | 101 | `TACTILE_SWITCH_SMD_12MM` |
| 45 | `E2-4` | 102 | `TACTILE_SWITCH_SMD_4.5MM` |
| 46 | `E2-5` | 103 | `TACTILE_SWITCH_SMD_4.6X2.8MM` |
| 47 | `E3,5-10` | 104 | `TACTILE_SWITCH_SMD_5.2MM` |
| 48 | `E3,5-8` | 105 | `TACTILE_SWITCH_SMD_6.0X3.5MM` |
| 49 | `E5-10,5` | 106 | `TACTILE_SWITCH_SMD_6.2MM_TALL` |
| 50 | `E5-13` | 107 | `TACTILE_SWITCH_SMD_RIGHT_ANGLE` |
| 51 | `E5-4` | 108 | `TO220` |
| 52 | `E5-5` | 109 | `TO220BV` |
| 53 | `E5-6` | 110 | `TO92` |
| 54 | `E5-8,5` | 111 | `TSSOP28` |
| 55 | `E7,5-16` | 112 | `WS2812B` |
| 56 | `E7,5-18` | 113 | `XL6019` |
| 57 | `EF-TRANSFORMER` | | |

## Files

| File | Description |
|------|-------------|
| `common components.lbr` | Eagle library (components, symbols, footprints) |
| `DesignRules.dru` | Eagle design rules |
