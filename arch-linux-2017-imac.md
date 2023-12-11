# Web browser tests on Arch Linux

## OS, system, and testing specs

- Arch Linux
  - Firmware v.515.0.0.0.0
  - Linux kernel 6.6.3-arch1-1
  - GNOME 45.1 / Wayland
- iMac 18,3 (mid-2017 iMac)
  - Intel® Core™ i7-7700K × 8, 64GB RAM
  - AMD Radeon™ Pro 580X running 3840x2160 at 2x
- Each browser running in private window; disabled extensions and tracking protection
- Each browser via Flathub unless otherwise noted

----

## Jetstream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | 1. | Brave | 1.61.101 | 120.0.6099.71 | 183.157 | 2023-12-08 |
| 2. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 182.543 | 2023-12-08 |
| 3. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 179.141 | 2023-12-08 |
| 4. | 4. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 174.299 | 2023-12-08 |
| 5. | - | Mozilla Firefox | 120.0.1 | - | 136.710 | 2023-12-08 |

[^UgC]: From the AUR as `ungoogled-chromium-bin`.

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Mozilla Firefox | 120.0.1 | - | 969.82 ± 2.79% | 2023-12-08 |
| 2. | 1. | Brave | 1.61.101 | 120.0.6099.71 | 969.30 ± 9.31% | 2023-12-08 |
| 3. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 958.93 ± 2.70% | 2023-12-08 |
| 4. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 829.41 ± 2.98% | 2023-12-08 |
| 5. | 4. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 819.25 ± 2.94%| 2023-12-08 |

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Mozilla Firefox | 120.0.1 | - | 202 ± 17 (8.3%) | 2023-12-08 |
| 2. | 1. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 189 ± 5.9 (3.1%) | 2023-12-08 |
| 3. | 2. | Brave | 1.61.101 | 120.0.6099.71 | 187 ± 5.5 (2.9%) | 2023-12-08 |
| 4. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 159 ± 6.6 (4.2%) | 2023-12-08 |
| 5. | 4. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 153 ± 3.8 (2.5%) | 2023-12-08 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Runs/<br>min. | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Mozilla Firefox | 120.0.1 | - | 221.0 | 2023-12-08 |
| 2. | 1. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 198.1 | 2023-12-08 |
| 3. | 2. | Brave | 1.61.101 | 120.0.6099.71 | 197.5 | 2023-12-08 |
| 4. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71  | 168.5 | 2023-12-08 |
| 5. | 4. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 158.8 | 2023-12-08 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Runs/<br>min. | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | 1. | Brave | 1.61.101 | 120.0.6099.71 | 171.6 | 2023-12-08 |
| 2. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 167.5 |
| 3. | - | Mozilla Firefox | 120.0.1 | - | 161.5 | 2023-12-08 |
| 4. | 3. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 139.8 | 2023-12-08 |
| 5. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71  | 136.2 | 2023-12-08 |

----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### JetStream raw data

Google Chrome v.120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Score: 182.543

Brave v.1.61.101 with Chromium: 120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Score: 183.157

Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
2023-12-08
Score: 179.141

Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-08
Score: 174.299

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-08
Score: 136.710

#### MotionMark raw data

Google Chrome v.120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Score: 958.93 ± 2.70% 

Brave v.1.61.101 with Chromium: 120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Score: 969.30 ± 9.31%

Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
2023-12-08
Score: 829.41 ± 2.98%

Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-08
Score: 819.25 ± 2.94%

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-08
Score: 969.82 ± 2.79%

#### Speedometer raw data

Google Chrome v.120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Arithmetic Mean: 189 ± 5.9 (3.1%)
Iteration 1	167.5 runs/min	<-- WORST
Iteration 2	188.5 runs/min
Iteration 3	189.7 runs/min
Iteration 4	186.9 runs/min
Iteration 5	198.1 runs/min	<-- BEST
Iteration 6	190.0 runs/min
Iteration 7	194.8 runs/min
Iteration 8	187.5 runs/min
Iteration 9	193.2 runs/min
Iteration 10	191.4 runs/min


Brave v.1.61.101 with Chromium: 120.0.6099.71 (Official Build) unknown (64-bit)
2023-12-08
Arithmetic Mean: 187 ± 5.5 (2.9%)
Iteration 1	171.6 runs/min	<-- WORST
Iteration 2	192.4 runs/min
Iteration 3	179.9 runs/min
Iteration 4	191.3 runs/min
Iteration 5	197.5 runs/min	<-- BEST
Iteration 6	186.9 runs/min
Iteration 7	190.6 runs/min
Iteration 8	183.9 runs/min
Iteration 9	192.9 runs/min
Iteration 10	182.2 runs/min


Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
2023-12-08
Arithmetic Mean: 159 ± 6.6 (4.2%)
Iteration 1	136.2 runs/min	<-- WORST
Iteration 2	151.0 runs/min
Iteration 3	166.3 runs/min
Iteration 4	161.2 runs/min
Iteration 5	158.4 runs/min
Iteration 6	161.4 runs/min
Iteration 7	161.7 runs/min
Iteration 8	163.1 runs/min
Iteration 9	168.5 runs/min	<-- BEST
Iteration 10	158.1 runs/min


Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-08
Arithmetic Mean: 153 ± 3.8 (2.5%)
Iteration 1	139.8 runs/min	<-- WORST
Iteration 2	158.8 runs/min	<-- BEST
Iteration 3	151.4 runs/min
Iteration 4	152.7 runs/min
Iteration 5	154.3 runs/min
Iteration 6	157.5 runs/min
Iteration 7	151.8 runs/min
Iteration 8	156.7 runs/min
Iteration 9	156.7 runs/min
Iteration 10	152.8 runs/min


Mozilla Firefox v.120.0.1 (64-bit)
2023-12-08
Arithmetic Mean: 202 ± 17 (8.3%)
Iteration 1	161.5 runs/min	<-- WORST
Iteration 2	205.8 runs/min
Iteration 3	218.5 runs/min
Iteration 4	215.6 runs/min
Iteration 5	208.9 runs/min
Iteration 6	212.8 runs/min
Iteration 7	213.8 runs/min
Iteration 8	221.0 runs/min	<-- BEST
Iteration 9	155.8 runs/min
Iteration 10	205.4 runs/min
