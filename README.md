# IoT-Sensors
This document provides a comprehensive reference for sensors, including their key specifications and datasheet links.

---

## Voltage Output Sensors

| Sensor | Application | Output Impedance | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|------------------|---------------|------------------------|----------------------|------------------------|----------------|
| LEICI 214-01 | pH | 5 kΩ | ±414 mV (828 mV) | ±20 mV (zero drift) | **±2.4%** | **~60** | [LEICI Product Center](https://www.lei-ci.com/product/234.html) |
| TSC1021 | Current | ≤ 10 Ω* | 0-5 V (5000 mV) | ±5 mV (input offset) | **±0.1%** | **~65** | [STMicroelectronics Datasheet](https://www.st.com/resource/en/datasheet/tsc1021.pdf) |
| Zemic L6D | Force | ≤ 1 kΩ | 0-20 mV/V (20 mV/V) | ±0.02 mV/V (zero balance) | **±0.1%** | **~75** | [Zemic Datasheet](https://www.zemic.com.cn/en/product/load-cells/single-point/l6d/) |
| MPM160 | Pressure | 4 kΩ | 0.5-4.5 V (4000 mV) | ±25 mV (zero offset) | **±0.63%** | **~80** | [MicroSensor Datasheet](https://www.microsensorcorp.com/Product/MPM160.html) |
| GZP193-201GF01 | Pressure | 5 kΩ | 0.5-4.5 V (4000 mV) | ±20 mV (zero offset) | **±0.5%** | **~80** | [Genuine Datasheet](https://www.genuine.com.cn/product/87.html) |
| LM35 | Temperature | 0.1 Ω | -0.55V to +1.5V (2050 mV) | ±0.5°C (5 mV) | **±0.24%** | **~52** | [TI LM35 Datasheet](https://www.ti.com.cn/document-viewer/cn/LM35/datasheet/33-ZHCSHC4H.html) |
| TMP36 | Temperature | 0.1 Ω | 0.1V to 2.0V (1900 mV) | ±1°C (10 mV) | **±0.53%** | **~50** | [Analog Devices TMP36](https://www.analog.com/en/products/tmp36.html) |
| LM335 | Temperature | 0.5 Ω | 2.33V to 3.73V (1400 mV) | ±1°C (10 mV) | **±0.71%** | **~55-65** | [TI LM335 Datasheet](https://www.ti.com/product/LM335) |
| Honeywell HIH-5031-001 | Humidity | 10 kΩ | 0.5-4.5 V (4000 mV) | ±0.2 V (200 mV) | **±5%** | **58-62** | [Honeywell Datasheet](https://www.datasheets.com/honeywell/HIH-5031-001) |
| Shinyei RHI Series | Humidity | -- | 0-3.3 V (3300 mV) | ±0.1 V (100 mV) | **±3%** | **55-65** | [Shinyei](https://www.shinyei.co.jp/STC/eng/products/humidity/rhi.html) |
| Veris HW2XA2A | Humidity | -- | 0-5/10 V (5000/10000 mV) | ±0.5 V (500 mV) | **±5-10%** | **34-38** | [Veris](https://www.veris.com/998052/Product/126859/category/126896/category/126838/category/humidity-sensors) |
| E+E HTP201 | Humidity | -- | 0-1/5/10 V (1000/5000/10000 mV) | ±0.3 V (300 mV) | **±3-30%** | **32-38** | [E+E](https://www.epluse.com/cn/products/humidity-instruments/humidity-modules-and-probes/htp201/) |
| EE06 Series | Humidity | -- | 0-1 V (1000 mV) | ±0.05 V (50 mV) | **±5%** | **30-35** | [EEWorld Datasheet](https://datasheet.eeworld.com.cn/view/1724359.html) |
| Silicon Labs Si7007 | Humidity | PWM output | PWM (0-VDD) | ±5% RH | **±5%** | **26-30** | [Silicon Labs](https://cn.silabs.com/sensors/humidity/si7007-22-23) |

*\*: add output buffer.*

---

## Current Output Sensors

| Sensor | Application | Output Impedance | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|------------------|---------------|------------------------|----------------------|------------------------|----------------|
| BH1620FVC-TR | Light | > 1 MΩ | 0-100 µA | 1-10 nA (dark current) | **0.001-0.01%** | **~90** | [ROHM Datasheet](https://www.rohm.com/products/sensors-mems/ambient-light-sensor-ics/analog-current-output/bh1620fvc-product) |
| APDS-9005 | Light | > 1 MΩ | 0-100 µA | 1-10 nA (dark current) | **0.001-0.01%** | **~90** | [Broadcom Datasheet](https://www.broadcom.com/products/optical-sensors/ambient-light-sensors/apds-9005) |
| VEMD5525FX02 | Light | > 10 MΩ | 0-50 µA | 0.5-5 nA (dark current) | **0.001-0.01%** | **~90** | [Vishay Datasheet](https://www.vishay.com/en/product/80560/) |
| BPW34 | Light | 10-100 MΩ | 0-100 µA | 1-10 nA (dark current) | **0.001-0.01%** | **~90** | [Vishay Datasheet](https://www.vishay.com/en/product/81566/) |
| Alpha Sense CO-A4 | Gas | 1-100 MΩ | ±100 µA (200 µA) | ±0.1 µA (baseline drift) | **±0.05%** | **~85** | [Alphasense Datasheet](https://www.alphasense.com/product/co-a4/) |
| GUVA-S12SD | UV | > 1 GΩ | 0-100 nA | 0.1-1 nA (dark current) | **0.1-1%** | **~70** | [Genicom Datasheet](https://www.genicom.com/product/guva-s12sd/) |
| **SGM446** | Temperature | > 10 MΩ | 218.2 µA @ -55°C to 423.2 µA @ +150°C (205 µA span) | ±2°C (calibration error) | **±0.98%** | **~45-50** | [SGMICRO](https://www.sg-micro.com/product-detail/SGM446) |
| **AD592CN** | Temperature | > 10 MΩ | 248.2 µA @ -25°C to 378.2 µA @ +105°C (130 µA span) | ±0.5°C @ 25°C, ±1°C full range | **±0.77%** | **~48-52** | [Omega](https://www.omega.com/en-us/sensors-and-sensing-equipment/temperature-sensors/thermistors-and-rtds/ad592/p/AD592CN) |
| **LMT01** | Temperature | Digital pulse output | Pulse frequency proportional to temperature | ±0.5°C (-20°C to 90°C) | **±0.5%** | **~55-60** | [Texas Instruments](https://www.ti.com/product/LMT01) |

---

## Resistive Output Sensors (NTC Thermistors)

| Type | Application | Resistance@0°C | Resistance@25°C | Resistance@85°C | Dynamic Range | Baseline Variable Range | Baseline Variable (%) | SNDR (Sensor Only, dB) | Datasheet Link |
|------|-------------|----------------|-----------------|-----------------|---------------|------------------------|----------------------|------------------------|----------------|
| MF58-105-4250 | NTC | 3,700 kΩ | 1,000 kΩ | 91 kΩ | 3,609 kΩ | ±10% R25 (100 kΩ) | **±2.8%** | **~32** | [MF58 Series Datasheet](https://www.lcsc.com/product-detail/NTC-Thermistors_Nanjing-Shiheng-Elec-MF58-104F3950_C123399.html) |
| NTCS0805E3684HXT | NTC | 1,680 kΩ | 680 kΩ | 72 kΩ | 1,608 kΩ | ±5% R25 (34 kΩ) | **±2.1%** | **~27** | [Vishay NTCS0805 Datasheet](https://www.vishay.com/en/product/thermistors/ntcs0805e3/) |
| 105NT-4-R025H46G | NTC | 3,420 kΩ | 1,000 kΩ | 82 kΩ | 3,338 kΩ | ±5% R25 (50 kΩ) | **±1.5%** | **~32** | [SEMITEC NT Series Datasheet](https://www.semitec.co.jp/english/products/thermistor/nt/) |
| GP105V8J | NTC | 2,880 kΩ | 1,000 kΩ | 80 kΩ | 2,800 kΩ | ±10% R25 (100 kΩ) | **±3.6%** | **~31** | [Littelfuse GP Series Datasheet](https://www.littelfuse.com/products/temperature-sensors/ntc-thermistors/glass-encapsulated/gp-series.aspx) |
| NTCG104QH105HT1 | NTC | 4,330 kΩ | 1,000 kΩ | 65 kΩ | 4,265 kΩ | ±3% R25 (30 kΩ) | **±0.7%** | **~36** | [TDK NTCG Series Datasheet](https://product.tdk.com/en/products/sensor/ntc/chip-ntc-thermistor/index.html) |
| MF58-504-4050 | NTC | 1,840 kΩ | 500 kΩ | 53 kΩ | 1,787 kΩ | ±10% R25 (50 kΩ) | **±2.8%** | **~31** | [MF58 Series Datasheet](https://www.digikey.hk/en/products/detail/cantherm/MF58104F3950/1840608) |
| EPCOS B57301V2472J60 | NTC | 45.9 kΩ | 4.7 kΩ | 560 Ω | 45.3 kΩ | ±3% R25 (141 Ω) | **±0.3%** | **~38** | [EPCOS B57301V2 Series Datasheet](https://www.tdk-electronics.tdk.com/en/ntc-thermistors) |

---

## Capacitive Output Sensors

| Sensor | Application | Capacitance Range | Baseline Variable Range | Baseline Variable (%) | Sensitivity | SNDR (Sensor Only, dB) | Datasheet Link |
|--------|-------------|-------------------|------------------------|----------------------|-------------|------------------------|----------------|
| **Precision Capacitive Displacement Sensor** | Displacement/Position | 10-100 pF (probe dependent) | ±0.5 pF (zero drift) | **±0.5-5%** | <0.1 nm resolution | **>60 dB** | [Baidu Baike](https://baike.baidu.com/item/%E7%94%B5%E5%AE%B9%E5%BC%8F%E4%BD%8D%E7%A7%BB%E4%BC%A0%E6%84%9F%E5%99%A8) |
| **IST AG K5** | Humidity | **200 pF ±50 pF** (250 pF span) | ±50 pF (initial tolerance) | **±20%** | -- | **~25-35** | [Farnell](https://at.farnell.com/en-AT/ist-innovative-sensor-technology/k5-200-pf-50-pf/humidity-sensor-5s-12v-tht/dp/3586988) |
| **IST AG P14 FemtoCap-G** | Humidity | **180 pF ±50 pF** (230 pF span) | ±50 pF (initial tolerance) | **±21.7%** | -- | **~25-35** | [IST AG](https://www.ist-ag.com/de/product/23?istr=257) |
| **ROTRONIC HygroMer WA-1** | Humidity | **220 pF ±50 pF** (270 pF span) | ±50 pF (initial tolerance) | **±18.5%** | 5th order polynomial | **~30-40** | [ROTRONIC](https://service.rotronic.com/products-manual/wa-1.html) |
| **Michell H8000** | Humidity | **250 pF ±15%** (287.5 pF span) | ±37.5 pF (initial tolerance) | **±13%** | **0.45 pF / %RH** | **~35-45** | [Michell](https://www.michell.com/us/products/h8000.htm) |
| **General Capacitive Pressure Sensor** | Pressure | **50-100 pF** (50 pF span) | ±5 pF (zero drift) | **±10%** | few pF variation | **~30-40** | [Avnet](https://my.avnet.com/abacus/solutions/technologies/sensors/pressure-sensors/core-technologies/capacitive/) |
| **HTS2230** | Humidity | **180-220 pF** (55% RH) | ±50 pF (initial tolerance) | **±2-8%** | **0.13 pF / %RH** | **~25-35** | [ISweek](https://www.isweek.cn/226.html) |
| **NXP PCF8883** | Proximity/Touch | **10-60 pF** (50 pF span) | ±5 pF (parasitic capacitance) | **±10%** | Adjustable sensitivity | **~40-50** | [DigiKey](https://www.digikey.cn/zh/product-highlight/n/nxp-semi/pcf8883-capacitive-proximity-switch) |
| **Azoteq IQS680** | Proximity/Touch | **2-200 pF** (198 pF span) | ±10 pF (parasitic capacitance) | **±5%** | 10-bit ATI | **~50-55** | [Sekorm](https://en.sekorm.com/doc/3182954.html) |
| **TI FDC1004** | Capacitive Sensing | **±15 pF** (30 pF span) | ±100 pF | **±333%** | **0.5 fF resolution** | **~45-55** | [Texas Instruments](https://www.ti.com.cn/document-viewer/cn/lit/html/ZHCSCQ6C) |
| **IEEE 2007 Capacitive Pressure Sensor** | Pressure | -- | ±2 pF (baseline drift) | **±X%** | ~25 pF/kPa (<1 kPa) | **~35-45** | [IEEE Xplore](https://ieeexplore.ieee.org/document/4388691) |
| **Sensirion General Capacitive Humidity Sensor** | Humidity | 100-200 pF (100 pF span) | ±20 pF (initial tolerance) | **±20%** | -- | **~30-40** | Industry standard reference |
| **General Capacitive Displacement Sensor** | Displacement/Position | **5-50 pF** (range dependent) | ±1 pF (initial offset) | **±2-10%** | **5-125 μm/V** | **~50 dB** | [Baidu Baike](https://baike.baidu.com/item/%E7%94%B5%E5%AE%B9%E5%BC%8F%E4%BD%8D%E7%A7%BB%E4%BC%A0%E6%84%9F%E5%99%A8/0) |
| **Precision Capacitive Displacement Sensor** | Micro-Displacement | **10-100 pF** (probe dependent) | ±0.5 pF (zero drift) | **±0.5-5%** | **<0.1 nm resolution** | **~52 dB** | [Baidu Baike](https://baike.baidu.com/item/%E7%94%B5%E5%AE%B9%E5%BC%8F%E4%BD%8D%E7%A7%BB%E4%BC%A0%E6%84%9F%E5%99%A8/0) |
| **ΔΣ Modulator Capacitive Interface** | IR Imaging | 0.1-5 pF (pixel-level) | ±0.01 pF (dark current comp) | **±0.2-1%** | 16-bit ENOB | **96.6 dB** | [MDPI Sensors, 2017](https://www.mdpi.com/1424-8220/17/6/1273) |

---

## Summary

| Category | Sensors |
|----------|--------|
| **Voltage Output** | LEICI 214-01, TSC1021, Zemic L6D, MPM160, GZP193-201GF01, LM35, TMP36, LM335, Honeywell HIH-5031-001, Shinyei RHI Series, Veris HW2XA2A, E+E HTP201, EE06 Series, Silicon Labs Si7007 |
| **Current Output** | BH1620FVC-TR, APDS-9005, VEMD5525FX02, BPW34, Alpha Sense CO-A4, GUVA-S12SD, SGM446, AD592CN, LMT01 |
| **Resistive Output** | MF58-105-4250, NTCS0805E3684HXT, 105NT-4-R025H46G, GP105V8J, NTCG104QH105HT1, MF58-504-4050, EPCOS B57301V2472J60 |
| **Capacitive Output** | MEMS Microphone Interface, SAR ADC Capacitor Reference, Precision Capacitive Displacement Sensor, ΔΣ Modulator Capacitive Interface, CMOS SC Capacitive Interface, IST AG K5, IST AG P14 FemtoCap-G, ROTRONIC HygroMer WA-1, Michell H8000, General Capacitive Pressure Sensor, NXP PCF8883, Azoteq IQS680, TI FDC1004, IEEE 2007 Capacitive Pressure Sensor, Sensirion General Capacitive Humidity Sensor, Dual-Mode Capacitive Sensor Interface |

---

## Statistical Summary by Category

### Voltage Output Sensors (14 sensors)

| Metric | Output Impedance (Ω) | Dynamic Range (mV) | Baseline Variable (%) | SNDR (dB) |
|--------|---------------------|-------------------|----------------------|-----------|
| **Minimum** | 0.1 | 828 | 0.1% | 26 |
| **Maximum** | 10,000 | 10,000 | 30% | 80 |
| **Average** | ~2,500 | ~3,200 | ~4.2% | ~55 |
| **Median** | 5 | ~3,000 | ~2.5% | ~58 |

*Note: Values exclude PWM output sensors for Dynamic Range calculation.*

---

### Current Output Sensors (9 sensors)

| Metric | Output Impedance (Ω) | Dynamic Range (µA) | Baseline Variable (%) | SNDR (dB) |
|--------|---------------------|-------------------|----------------------|-----------|
| **Minimum** | 1,000,000 | 50 | 0.001% | 45 |
| **Maximum** | 1,000,000,000 | 205 | 1% | 90 |
| **Average** | ~222,000,000 | ~130 | ~0.35% | ~73 |
| **Median** | ~10,000,000 | ~130 | ~0.05% | ~70 |

*Note: SGM446 and AD592CN are current-output temperature sensors with lower SNDR (45-52 dB), expanding the current output SNDR range downward.*

---

### Resistive Output Sensors (7 sensors)

| Metric | Resistance@25°C (kΩ) | Dynamic Range (kΩ) | Baseline Variable (%) | SNDR (dB) |
|--------|---------------------|-------------------|----------------------|-----------|
| **Minimum** | 4.7 | 1,608 | 0.3% | 27 |
| **Maximum** | 1,000 | 4,265 | 3.6% | 38 |
| **Average** | ~690 | ~3,100 | ~2.3% | ~32 |
| **Median** | 680 | ~3,338 | ~2.1% | ~32 |

---

### Capacitive Output Sensors (19 sensors)

| Metric | Capacitance Range (pF) | Dynamic Range (pF) | Baseline Variable (%) | SNDR (dB) |
|--------|-----------------------|-------------------|----------------------|-----------|
| **Minimum** | 0.1 | 30 | 0.1% | 25 |
| **Maximum** | 287.5 | 270 | 333% | 96.6 |
| **Average** | ~85 | ~100 | ~28% | ~55 |
| **Median** | ~30 | ~50 | ~10% | ~45 |

*Note: TI FDC1004's 333% baseline variable is due to offset compensation capability. ΔΣ modulator interface achieves 96.6 dB SNDR, significantly higher than typical capacitive sensors.*

---

## Overall Statistical Summary (All Sensors)

| Metric | Output Impedance | Dynamic Range | Baseline Variable (%) | SNDR (dB) |
|--------|-----------------|---------------|----------------------|-----------|
| **Minimum** | 0.1 Ω | 20 µV/V (Zemic) | 0.001% | 25 |
| **Maximum** | 1 GΩ | 10,000 mV | 333% | 96.6 |
| **Overall Average** | ~55 MΩ | -- | ~11% | ~52 |
| **Highest SNDR** | 96.6 dB (ΔΣ Modulator Capacitive Interface) |
| **Lowest SNDR** | 25 dB (Capacitive Humidity Sensors) |

---

## SNDR Distribution by Category

| SNDR Range (dB) | Voltage Output | Current Output | Resistive Output | Capacitive Output |
|-----------------|---------------|---------------|------------------|-------------------|
| **0-30** | 1 | 0 | 1 | 4 |
| **30-40** | 2 | 0 | 6 | 4 |
| **40-50** | 1 | 2 | 0 | 4 |
| **50-60** | 3 | 1 | 0 | 3 |
| **60-70** | 3 | 0 | 0 | 2 |
| **70-80** | 3 | 1 | 0 | 0 |
| **80-90** | 1 | 4 | 0 | 0 |
| **90-100** | 0 | 1 | 0 | 2 |

---

## Key Observations

| Category | Lowest Baseline Variable | Highest Baseline Variable | SNDR Range |
|----------|-------------------------|--------------------------|------------|
| **Voltage Output** | 0.1% (TSC1021, Zemic L6D) | 30% (E+E HTP201) | 26-80 dB |
| **Current Output** | 0.001% (Photodiodes) | 1% (GUVA-S12SD) | 45-90 dB |
| **Resistive Output** | 0.3% (EPCOS B57301) | 3.6% (GP105V8J) | 27-38 dB |
| **Capacitive Output** | 0.1% (SAR ADC Capacitor Reference) | 333% (TI FDC1004) | 25-96.6 dB |

---

## SNDR Ranking (Sensor Only, Lowest to Highest)

| Rank | Sensor | Category | SNDR (dB) |
|------|--------|----------|-----------|
| 1 | IST AG K5 / P14 | Capacitive | 25-35 |
| 2 | Silicon Labs Si7007 | Voltage | 26-30 |
| 3 | NTCS0805E3684HXT | Resistive | ~27 |
| 4 | EE06 Series | Voltage | 30-35 |
| 5 | ROTRONIC HygroMer WA-1 | Capacitive | 30-40 |
| 6 | GP105V8J, MF58-504-4050 | Resistive | ~31 |
| 7 | MF58-105-4250, 105NT-4-R025H46G | Resistive | ~32 |
| 8 | Veris HW2XA2A, E+E HTP201 | Voltage | 32-38 |
| 9 | NTCG104QH105HT1 | Resistive | ~36 |
| 10 | EPCOS B57301V2472J60 | Resistive | ~38 |
| 11 | Michell H8000, IEEE 2007 | Capacitive | 35-45 |
| 12 | NXP PCF8883 | Capacitive | 40-50 |
| 13 | SGM446 | Current | 45-50 |
| 14 | TI FDC1004 | Capacitive | 45-55 |
| 15 | TMP36 | Voltage | ~50 |
| 16 | Azoteq IQS680 | Capacitive | 50-55 |
| 17 | AD592CN | Current | 48-52 |
| 18 | LM35 | Voltage | ~52 |
| 19 | LM335 | Voltage | 55-65 |
| 20 | Shinyei RHI Series | Voltage | 55-65 |
| 21 | LMT01 | Current | 55-60 |
| 22 | Honeywell HIH-5031-001 | Voltage | 58-62 |
| 23 | SAR ADC Capacitor Reference | Capacitive | 60.4 |
| 24 | MEMS Microphone Interface | Capacitive | 65.4 |
| 25 | GUVA-S12SD | Current | ~70 |
| 26 | Zemic L6D | Voltage | ~75 |
| 27 | LEICI 214-01, MPM160, GZP193 | Voltage | ~80 |
| 28 | Alpha Sense CO-A4 | Current | ~85 |
| 29 | TSC1021 | Voltage | ~85 |
| 30 | BH1620FVC-TR, APDS-9005, VEMD5525FX02, BPW34 | Current | ~90 |
| 31 | ΔΣ Modulator Capacitive Interface | Capacitive | 96.6 |

---

## Notes

- **Output Impedance Values**: Based on manufacturer specifications
- **Access Dates**: All links accessed March 30, 2026
- **MF58 Series**: Manufactured by multiple suppliers including Nanjing Shiheng, Cantherm, and Xingxiang Electronics
- **NTC Series**: Various manufacturers including Vishay, SEMITEC, Littelfuse, TDK, and EPCOS
- **Capacitive Sensors**: Includes humidity, pressure, proximity/touch, displacement, acoustic, and interface circuits
- **Current Output Sensors**: Added SGM446, AD592CN (analog current-output temperature sensors) and LMT01 (digital pulse-output temperature sensor)
- **\* Output Buffer**: Indicates sensors requiring an output buffer for proper signal conditioning
- **SNDR (Sensor Only)**: Estimated based on sensor's inherent dynamic range, noise characteristics, and linearity. Does not include external signal conditioning or ADC contributions.
- **Baseline Variable (%)**: Calculated as (Baseline Variable Range / Full Scale Dynamic Range) × 100%. For TI FDC1004, the high percentage (333%) is due to its offset compensation feature, which allows cancellation of large parasitic capacitance while measuring small signal changes.
- **Statistical Averages**: Calculated using nominal values; ranges are represented by midpoints for averaging purposes.
- **New Additions**: Added 3 current-output temperature sensors (SGM446, AD592CN, LMT01) with SNDR ranging from 45-60 dB, filling the lower SNDR range in current output category.
