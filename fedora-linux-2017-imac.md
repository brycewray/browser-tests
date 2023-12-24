# Web browser tests on Fedora Linux

*OS, system, and testing specs at bottom.*

----

## [Speedometer 2.1](https://browserbench.org/Speedometer2.1/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | 215 ± 7.6 (3.6%) | 2023-12-22 |
| 2. | 2. | Google Chrome | 208 ± 8.0 (3.8%) | 2023-12-21 |
| 3. | 3. | Brave | 201 ± 7.6 (3.8%) | 2023-12-21 |1
| 4. | &mdash; | Mozilla Firefox | 197 ± 8.3 (4.2%) | 2023-12-24 |
| 5. | 4. | Opera | 192 ± 6.3 (3.3%) | 2023-12-23 |
| 6. | 5. | Microsoft Edge | 167 ± 3.9 (2.3%) | 2023-12-21 |
| 7. | 6. | Ungoogled Chromium | 160 ± 2.8 (1.8%) | 2023-12-21 |

----

## [JetStream 2.1](https://browserbench.org/JetStream/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | 180.414 | 2023-12-22 |
| 2. | 2. | Google Chrome | 180.385 | 2023-12-21 |
| 3. | 3. | Brave | 180.141 | 2023-12-21 |
| 4. | 4. | Opera | 179.150 | 2023-12-23 |
| 5. | 5. | Microsoft Edge | 173.661 | 2023-12-21 |
| 6. | 6. | Ungoogled Chromium | 165.990 | 2023-12-21 |
| 7. | &mdash; | Mozilla Firefox | 127.624 | 2023-12-24 |

----

## [MotionMark 1.2](https://browserbench.org/MotionMark1.2/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 2419.74[^real] ± 3.03% | 2023-12-21 |
| 2. | 2. | Brave | 964.59 ± 2.67% | 2023-12-21 |
| 3. | 3. | Vivaldi | 956.89 ± 2.86% | 2023-12-22 |
| 4. | 4. | Opera | 939.81 ± 2.29% | 2023-12-23 |
| 5. | 5. | Ungoogled Chromium | 848.31 ± 2.37% | 2023-12-21 |
| 6. | 6. | Microsoft Edge | 838.67 ± 2.32% | 2023-12-21 |
| 7. | &mdash; | Mozilla Firefox | 208.68[^real] ± 4.69% | 2023-12-24 |

[^real]: Not a typo.

----

## OS, system, and testing specs

- Fedora Linux 39 (Workstation Edition)
  - Firmware v.515.0.0.0.0
  - Kernel: Linux 6.6.7-200.fc39.x86_64
  - GNOME 45.2 / Wayland
- iMac 18,3 (mid-2017 iMac)
  - Intel® Core™ i7-7700K × 8, 64GB RAM
  - AMD Radeon™ Pro 580X running 3840 × 2160 at 2x
- Each browser is [current stable desktop version](/browsers.md) on date of test, running in a private window with disabling of all extensions and tracking protection. No other browsers are running at the time.
- On MotionMark test, all results “on a large screen (desktop)” as per instructions.

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit) - Google repo
2023-12-21
Arithmetic Mean: 208 ± 8.0 (3.8%)

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit) - Brave repo
2023-12-21
Arithmetic Mean: 201 ± 7.6 (3.8%)
Iteration 1	181.5 runs/min

Microsoft Edge v.120.0.2210.91 (Official build) (64-bit) - Microsoft repo
Chromium v.120.0.6099.130
2023-12-21
Arithmetic Mean: 167 ± 3.9 (2.3%)

Vivaldi v.6.5.3206.42 (Stable channel) stable (64-bit) - Vivaldi repo
Chromium v.120.0.6099.121
2023-12-22
Arithmetic Mean: 215 ± 7.6 (3.6%)

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit) - Flathub
2023-12-21
Arithmetic Mean: 160 ± 2.8 (1.8%)

Mozilla Firefox v.121.0 (64-bit) - Fedora repo
2023-12-24
Arithmetic Mean: 197 ± 8.3 (4.2%)

Opera v.106.0.4998.19
Chromium v.120.0.6099.130
2023-12-23
Arithmetic Mean: 192 ± 6.3 (3.3%)


#### JetStream raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit) - Google repo
2023-12-21
Score: 180.385

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit) - Brave repo
2023-12-21
Score: 180.141

Microsoft Edge v.120.0.2210.91 (Official build) (64-bit) - Microsoft repo
Chromium v.120.0.6099.130
2023-12-21
Score: 173.661

Vivaldi v.6.5.3206.42 (Stable channel) stable (64-bit) - Vivaldi repo
Chromium v.120.0.6099.121
2023-12-22
Score: 180.414

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit) - Flathub
2023-12-21
Score: 165.990

Mozilla Firefox v.121.0 (64-bit) - Fedora repo
2023-12-24
Score: 127.624

Opera v.106.0.4998.19
Chromium v.120.0.6099.130
2023-12-23
Score: 179.150


#### MotionMark raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit) - Google repo
2023-12-21
Score: 2419.74 ± 3.03%

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit) - Brave repo
2023-12-21
Score: 964.59 ± 2.67%

Microsoft Edge v.120.0.2210.91 (Official build) (64-bit) - Microsoft repo
Chromium v.120.0.6099.130
2023-12-21
Score: 838.67 ± 2.32%

Vivaldi v.6.5.3206.42 (Stable channel) stable (64-bit) - Vivaldi repo
Chromium v.120.0.6099.121
2023-12-22
Score: 956.89 ± 2.86%

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit) - Flathub
2023-12-21
Score: 848.31 ± 2.37%

Mozilla Firefox v.121.0 (64-bit) - Fedora repo
2023-12-24
Score: 208.68 ± 4.69%

Opera v.106.0.4998.19
Chromium v.120.0.6099.130
2023-12-23
Score: 939.81 ± 2.29%

-->