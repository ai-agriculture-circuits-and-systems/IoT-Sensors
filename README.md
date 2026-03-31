# IoT-Sensors
This document provides a comprehensive reference for sensors, including their key specifications and datasheet links.

---

## Voltage Output Sensors
| Sensor | Application | Output Impedance | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|------------------|---------------|------------------------|----------------------|------------------------|----------------|
| LEICI 214-01 | pH | 5 kΩ | ±414 mV (828 mV) | ±20 mV (零点漂移) | **±2.4%** | **~80** | [LEICI Product Center](https://www.lei-ci.com/product/234.html) |
| TSC1021 | Current | ≤ 10 Ω* | 0-5 V (5000 mV) | ±5 mV (输入失调) | **±0.1%** | **~85** | [STMicroelectronics Datasheet](https://www.st.com/resource/en/datasheet/tsc1021.pdf) |
| Zemic L6D | Force | ≤ 1 kΩ | 0-20 mV/V (20 mV/V) | ±0.02 mV/V (零点平衡) | **±0.1%** | **~75** | [Zemic Datasheet](https://www.zemic.com.cn/en/product/load-cells/single-point/l6d/) |
| MPM160 | Pressure | 4 kΩ | 0.5-4.5 V (4000 mV) | ±25 mV (零点偏移) | **±0.63%** | **~80** | [MicroSensor Datasheet](https://www.microsensorcorp.com/Product/MPM160.html) |
| GZP193-201GF01 | Pressure | 5 kΩ | 0.5-4.5 V (4000 mV) | ±20 mV (零点偏移) | **±0.5%** | **~80** | [Genuine Datasheet](https://www.genuine.com.cn/product/87.html) |
| LM35 | Temperature | 0.1 Ω | -0.55V 至 +1.5V (2050 mV) | ±0.5°C (5 mV) | **±0.24%** | **~52** | [TI LM35 Datasheet](https://www.ti.com.cn/document-viewer/cn/LM35/datasheet/33-ZHCSHC4H.html) |
| TMP36 | Temperature | 0.1 Ω | 0.1V 至 2.0V (1900 mV) | ±1°C (10 mV) | **±0.53%** | **~50** | [Analog Devices TMP36](https://www.analog.com/en/products/tmp36.html) |
| LM335 | Temperature | 0.5 Ω | 2.33V 至 3.73V (1400 mV) | ±1°C (10 mV) | **±0.71%** | **~55-65** | [TI LM335 Datasheet](https://www.ti.com/product/LM335) |
| Sensirion SHT31-ARP-B | Humidity | 10 kΩ | 0-3 V (3000 mV) | ±0.2 V (200 mV) | **±6.7%** | **70-75** | [Sensirion](https://www.sensirion.com/cn/products/catalog/SHT31-ARP-B) |
| Sensirion SHT30-ARP-B | Humidity | 10 kΩ | 0-3 V (3000 mV) | ±0.3 V (300 mV) | **±10%** | **65-70** | [Sensirion](https://www.sensirion.com/cn/products/catalog/SHT30-ARP-B) |
| DFRobot Gravity SHT30 | Humidity | 10 kΩ | 0.3-2.7 V (2400 mV) | ±0.2 V (200 mV) | **±8.3%** | **70-75** | [DFRobot Wiki](https://wiki.dfrobot.com.cn/_SKU_DFR0588_Gravity_SHT30%E6%A8%A1%E6%8B%9F%E6%B8%A9%E6%B9%BF%E5%BA%A6%E4%BC%A0%E6%84%9F%E5%99%A8) |
| Honeywell HIH-5031-001 | Humidity | 10 kΩ | 0.5-4.5 V (4000 mV) | ±0.2 V (200 mV) | **±5%** | **58-62** | [Honeywell Datasheet](https://www.datasheets.com/honeywell/HIH-5031-001) |
| Shinyei RHI Series | Humidity | 未明确 | 0-3.3 V (3300 mV) | ±0.1 V (100 mV) | **±3%** | **55-65** | [Shinyei](https://www.shinyei.co.jp/STC/eng/products/humidity/rhi.html) |
| Veris HW2XA2A | Humidity | 未明确 | 0-5/10 V (5000/10000 mV) | ±0.5 V (500 mV) | **±5-10%** | **34-38** | [Veris](https://www.veris.com/998052/Product/126859/category/126896/category/126838/category/humidity-sensors) |
| E+E HTP201 | Humidity | 未明确 | 0-1/5/10 V (1000/5000/10000 mV) | ±0.3 V (300 mV) | **±3-30%** | **32-38** | [E+E](https://www.epluse.com/cn/products/humidity-instruments/humidity-modules-and-probes/htp201/) |
| EE06 Series | Humidity | 未明确 | 0-1 V (1000 mV) | ±0.05 V (50 mV) | **±5%** | **30-35** | [EEWorld Datasheet](https://datasheet.eeworld.com.cn/view/1724359.html) |
| Silicon Labs Si7007 | Humidity | PWM输出 | PWM (0-VDD) | ±5% RH | **±5%** | **26-30** | [Silicon Labs](https://cn.silabs.com/sensors/humidity/si7007-22-23) |

*\*: add output buffer.*

---

## Current Output Sensors

| Sensor | Application | Output Impedance | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|------------------|---------------|------------------------|----------------------|------------------------|----------------|
| BH1620FVC-TR (Used in this work) | Light | > 1 MΩ | 0-100 µA | 1-10 nA (暗电流) | **0.001-0.01%** | **~90** | [ROHM Datasheet](https://www.rohm.com/products/sensors-mems/ambient-light-sensor-ics/analog-current-output/bh1620fvc-product) |
| APDS-9005 | Light | > 1 MΩ | 0-100 µA | 1-10 nA (暗电流) | **0.001-0.01%** | **~90** | [Broadcom Datasheet](https://www.broadcom.com/products/optical-sensors/ambient-light-sensors/apds-9005) |
| VEMD5525FX02 | Light | > 10 MΩ | 0-50 µA | 0.5-5 nA (暗电流) | **0.001-0.01%** | **~90** | [Vishay Datasheet](https://www.vishay.com/en/product/80560/) |
| BPW34 | Light | 10-100 MΩ | 0-100 µA | 1-10 nA (暗电流) | **0.001-0.01%** | **~90** | [Vishay Datasheet](https://www.vishay.com/en/product/81566/) |
| Alpha Sense CO-A4 | Gas | 1-100 MΩ | ±100 µA (200 µA) | ±0.1 µA (基线漂移) | **±0.05%** | **~85** | [Alphasense Datasheet](https://www.alphasense.com/product/co-a4/) |
| GUVA-S12SD | UV | > 1 GΩ | 0-100 nA | 0.1-1 nA (暗电流) | **0.1-1%** | **~70** | [Genicom Datasheet](https://www.genicom.com/product/guva-s12sd/) |

---

## Resistive Output Sensors (NTC Thermistors)

| Type | Application | Resistance@0°C | Resistance@25°C | Resistance@85°C | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|------|-------------|----------------|-----------------|-----------------|---------------|------------------------|----------------------|------------------------|----------------|
| MF58-105-4250 (Used in this work) | NTC | 3,700 kΩ | 1,000 kΩ | 91 kΩ | 3,609 kΩ | ±10% R25 (100 kΩ) | **±2.8%** | **~32** | [MF58 Series Datasheet](https://www.lcsc.com/product-detail/NTC-Thermistors_Nanjing-Shiheng-Elec-MF58-104F3950_C123399.html) |
| NTCS0805E3684HXT | NTC | 1,680 kΩ | 680 kΩ | 72 kΩ | 1,608 kΩ | ±5% R25 (34 kΩ) | **±2.1%** | **~27** | [Vishay NTCS0805 Datasheet](https://www.vishay.com/en/product/thermistors/ntcs0805e3/) |
| 105NT-4-R025H46G | NTC | 3,420 kΩ | 1,000 kΩ | 82 kΩ | 3,338 kΩ | ±5% R25 (50 kΩ) | **±1.5%** | **~32** | [SEMITEC NT Series Datasheet](https://www.semitec.co.jp/english/products/thermistor/nt/) |
| GP105V8J | NTC | 2,880 kΩ | 1,000 kΩ | 80 kΩ | 2,800 kΩ | ±10% R25 (100 kΩ) | **±3.6%** | **~31** | [Littelfuse GP Series Datasheet](https://www.littelfuse.com/products/temperature-sensors/ntc-thermistors/glass-encapsulated/gp-series.aspx) |
| NTCG104QH105HT1 | NTC | 4,330 kΩ | 1,000 kΩ | 65 kΩ | 4,265 kΩ | ±3% R25 (30 kΩ) | **±0.7%** | **~36** | [TDK NTCG Series Datasheet](https://product.tdk.com/en/products/sensor/ntc/chip-ntc-thermistor/index.html) |
| MF58-504-4050 | NTC | 1,840 kΩ | 500 kΩ | 53 kΩ | 1,787 kΩ | ±10% R25 (50 kΩ) | **±2.8%** | **~31** | [MF58 Series Datasheet](https://www.digikey.hk/en/products/detail/cantherm/MF58104F3950/1840608) |
| EPCOS B57301V2472J60 | NTC | 45.9 kΩ | 4.7 kΩ | 560 Ω | 45.3 kΩ | ±3% R25 (141 Ω) | **±0.3%** | **~38** | [EPCOS B57301V2 Series Datasheet](https://www.tdk-electronics.tdk.com/en/ntc-thermistors) |
---

## Capacitive Output Sensors (NTC Thermistors)

| Sensor | Application | Capacitance Range | Baseline Variable Range | Baseline Variable (%) | Sensitivity | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|-------------------|------------------------|----------------------|-------------|------------------------|----------------|
| **IST AG K5** | 湿度 | **200 pF ±50 pF** (250 pF动态) | ±50 pF (初始容差) | **±20%** | 未明确 | **~25-35** | [Farnell](https://at.farnell.com/en-AT/ist-innovative-sensor-technology/k5-200-pf-50-pf/humidity-sensor-5s-12v-tht/dp/3586988) |
| **IST AG P14 FemtoCap-G** | 湿度 | **180 pF ±50 pF** (230 pF动态) | ±50 pF (初始容差) | **±21.7%** | 未明确 | **~25-35** | [IST AG](https://www.ist-ag.com/de/product/23?istr=257) |
| **ROTRONIC HygroMer WA-1** | 湿度 | **220 pF ±50 pF** (270 pF动态) | ±50 pF (初始容差) | **±18.5%** | 5阶多项式输出 | **~30-40** | [ROTRONIC](https://service.rotronic.com/products-manual/wa-1.html) |
| **Michell H8000** | 湿度 | **250 pF ±15%** (287.5 pF动态) | ±37.5 pF (初始容差) | **±13%** | **0.45 pF / %RH** | **~35-45** | [Michell](https://www.michell.com/us/products/h8000.htm) |
| **通用电容式压力传感器** | 压力 | **50-100 pF** (50 pF动态) | ±5 pF (零点漂移) | **±10%** | 变化量几pF | **~30-40** | [Avnet](https://my.avnet.com/abacus/solutions/technologies/sensors/pressure-sensors/core-technologies/capacitive/) |
| **NXP PCF8883** | 接近/触摸 | **10-60 pF** (50 pF动态) | ±5 pF (寄生电容) | **±10%** | 可调灵敏度 | **~40-50** | [DigiKey](https://www.digikey.cn/zh/product-highlight/n/nxp-semi/pcf8883-capacitive-proximity-switch) |
| **Azoteq IQS680** | 接近/触摸 | **2-200 pF** (198 pF动态) | ±10 pF (寄生电容) | **±5%** | 10-bit ATI | **~50-55** | [Sekorm](https://en.sekorm.com/doc/3182954.html) |
| **TI FDC1004** | 电容式感应 | **±15 pF** (30 pF动态) | ±100 pF (偏移补偿) | **±333%** | **0.5 fF 分辨率** | **~45-55** | [德州仪器](https://www.ti.com.cn/document-viewer/cn/lit/html/ZHCSCQ6C) |
| **IEEE 2007 电容式压力传感器** | 压力 | 未明确具体pF值 | ±2 pF (基线漂移) | **±X%** | ~25 pF/kPa (<1 kPa) | **~35-45** | [IEEE Xplore](https://ieeexplore.ieee.org/document/4388691) |
| **Sensirion 通用电容式湿度传感器** | 湿度 | 100-200 pF (100 pF动态) | ±20 pF (初始容差) | **±20%** | 未明确 | **~30-40** | 行业标准参考 |
---

## Summary

| Category | Sensors |
|----------|--------|
| **Voltage Output** | E-201-C, TSC1021, EX-501, 5TC-GG-K-20-36, Zemic L6D, MPM160, GZP193-201GF01 |
| **Current Output** | BH1620FVC-TR, APDS-9005, VEMD5525FX02, BPW34, Alpha Sense CO-A4, GUVA-S12SD |
| **Resistive Output** | MF58-105-4250, NTCS0805E3684HXT, 105NT-4-R025H46G, GP105V8J, NTCG104QH105HT1, MF58-504-4050 |

---

## Notes

- **Output Impedance Values**: Based on manufacturer specifications
- **Access Dates**: All links accessed March 30, 2026
- **MF58 Series**: Manufactured by multiple suppliers including Nanjing Shiheng, Cantherm, and Xingxiang Electronics
- **\* Output Buffer**: Indicates sensors requiring an output buffer for proper signal conditioning
