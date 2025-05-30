---
product: CH32V303-EVT
cpu: CH32V303
cpu_core: QingKe V4F
ram: 64KB(SRAM)

vendor: wch-ch32v303-evb
board_variant: [
    cbt6,
    rbt6,
    rct6,
    vct6,
]
cpu_arch: [
    wch-v4f,
]
---


# CH32V303

## Test Environment

### Operating System Information

- RT-Thread / FreeRTOS
    - Source Code Link: [GitHub Repository](https://github.com/Community-PIO-CH32V/ch32-pio-projects)
    - Reference Installation Document:
        - PlatformIO Core: [Installation Guide](https://docs.platformio.org/en/latest/core/installation/index.html)
        - PlatformIO for CH32V: [Installation Instructions](https://pio-ch32v.readthedocs.io/en/latest/installation.html)

### Hardware Information

- CH32V303VCT6-EVT-R0-1v0

## Test Results

| Software Category | Package Name | Test Results (Test Report) |
| ----------------- | ------------ | -------------------------- |
| FreeRTOS          | N/A          | [Success][FreeRTOS]        |
| RT-Thread         | N/A          | [Success][RTThread]        |

[FreeRTOS]: ./FreeRTOS/README.md
[RTThread]: ./RT-Thread/README.md
