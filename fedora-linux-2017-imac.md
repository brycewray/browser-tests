# Web browser tests on Fedora Linux

## OS, system, and testing specs

- Fedora Linux 39 (Workstation Edition)
  - Firmware v.515.0.0.0.0
  - Kernel: Linux 6.6.7-200.fc39.x86_64
  - GNOME 45.2 / Wayland
- iMac 18,3 (mid-2017 iMac)
  - Intel® Core™ i7-7700K × 8, 64GB RAM
  - AMD Radeon™ Pro 580X running 3840 × 2160 at 2x
- Each browser running in private window; disabled extensions and tracking protection

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 215 ± 7.9 (3.7%) | 2023-12-21 |
| 2. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 214 ± 12 (5.8%) | 2023-12-21 |
| 3. | 2. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 208 ± 8.0 (3.8%) | 2023-12-21 |
| 4. | 3. | Brave | Brave | 1.61.109 | 120.0.6099.144 | 201 ± 7.6 (3.8%) | 2023-12-21 |1
| 5. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 187 ± 5.6 (3.0%) | 2023-12-21 |
| 6. | 4. | Microsoft Edge | Microsoft | 120.0.2210.89 | 120.0.6099.110 | 170 ± 3.5 (2.0%) | 2023-12-21 |
| 7. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.129 | 119.0.6099.129 | 160 ± 2.8 (1.8%) | 2023-12-21 |

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 180.385 | 2023-12-21 |
| 2. | 2. | Brave | Brave | 1.61.109 | 120.0.6099.144 | 180.141 | 2023-12-21 |
| 3. | 3. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 176.882 | 2023-12-21 |
| 4. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 175.833 | 2023-12-21 |
| 5. | 4. | Microsoft Edge | Microsoft | 120.0.2210.89 | 120.0.6099.110 | 174.439 | 2023-12-21 |
| 6. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.129 | 119.0.6099.129 | 165.990 | 2023-12-21 |
| 7. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 129.801 | 2023-12-21 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 2419.74 ± 3.03%[^real] | 2023-12-21 |
| 2. | 2. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 986.92 ± 2.87% | 2023-12-21 |
| 3. | 3. | Brave | Brave | 1.61.109 | 120.0.6099.144 | 964.59 ± 2.67% | 2023-12-21 |
| 4. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 955.36 ± 2.76% | 2023-12-21 |
| 5. | 4. | Ungoogled Chromium | Flathub | 119.0.6099.129 | 119.0.6099.129 | 848.31 ± 2.37% | 2023-12-21 |
| 6. | 5. | Microsoft Edge | Microsoft | 120.0.2210.89 | 120.0.6099.110 | 842.76 ± 5.47% | 2023-12-21 |
| 7. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 259.37 ± 2.31% | 2023-12-21 |

[^real]: Not a typo.

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-21
Arithmetic Mean: 208 ± 8.0 (3.8%)
Iteration 1	179.4 runs/min
Iteration 2	206.1 runs/min
Iteration 3	210.1 runs/min
Iteration 4	212.4 runs/min
Iteration 5	208.9 runs/min
Iteration 6	203.6 runs/min
Iteration 7	219.4 runs/min
Iteration 8	209.5 runs/min
Iteration 9	217.8 runs/min
Iteration 10	212.9 runs/min

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit)
2023-12-21
Arithmetic Mean: 201 ± 7.6 (3.8%)
Iteration 1	181.5 runs/min
Iteration 2	202.6 runs/min
Iteration 3	198.6 runs/min
Iteration 4	196.5 runs/min
Iteration 5	212.7 runs/min
Iteration 6	213.9 runs/min
Iteration 7	191.6 runs/min
Iteration 8	210.8 runs/min
Iteration 9	193.0 runs/min
Iteration 10	208.6 runs/min

Microsoft Edge v.120.0.2210.89 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-21
Arithmetic Mean: 170 ± 3.5 (2.0%)
Iteration 1	158.4 runs/min
Iteration 2	170.4 runs/min
Iteration 3	169.4 runs/min
Iteration 4	168.7 runs/min
Iteration 5	174.9 runs/min
Iteration 6	167.3 runs/min
Iteration 7	168.6 runs/min
Iteration 8	175.4 runs/min
Iteration 9	172.7 runs/min
Iteration 10	172.5 runs/min

Vivaldi v.6.5.3206.39 (Stable channel) stable (64-bit)
Chromium v.120.0.6099.121
2023-12-21
Arithmetic Mean: 215 ± 7.9 (3.7%)
Iteration 1	192.0 runs/min
Iteration 2	212.5 runs/min
Iteration 3	203.8 runs/min
Iteration 4	223.3 runs/min
Iteration 5	223.4 runs/min
Iteration 6	208.2 runs/min
Iteration 7	222.0 runs/min
Iteration 8	220.8 runs/min
Iteration 9	220.5 runs/min
Iteration 10	226.8 runs/min

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit)
2023-12-21
Arithmetic Mean: 160 ± 2.8 (1.8%)
Iteration 1	156.2 runs/min
Iteration 2	164.0 runs/min
Iteration 3	167.7 runs/min
Iteration 4	155.1 runs/min
Iteration 5	155.5 runs/min
Iteration 6	157.5 runs/min
Iteration 7	158.9 runs/min
Iteration 8	160.4 runs/min
Iteration 9	160.2 runs/min
Iteration 10	160.6 runs/min

Mozilla Firefox v.121.0 (64-bit)
2023-12-21
Arithmetic Mean: 214 ± 12 (5.8%)
Iteration 1	167.8 runs/min
Iteration 2	229.6 runs/min
Iteration 3	223.4 runs/min
Iteration 4	219.3 runs/min
Iteration 5	213.5 runs/min
Iteration 6	222.8 runs/min
Iteration 7	205.9 runs/min
Iteration 8	223.7 runs/min
Iteration 9	216.0 runs/min
Iteration 10	215.7 runs/min

GNOME Web/Epiphany v.45.1
2023-12-21
Arithmetic Mean: 187 ± 5.6 (3.0%)
Iteration 1	168.1 runs/min
Iteration 2	182.8 runs/min
Iteration 3	184.2 runs/min
Iteration 4	191.3 runs/min
Iteration 5	196.0 runs/min
Iteration 6	185.3 runs/min
Iteration 7	187.6 runs/min
Iteration 8	192.7 runs/min
Iteration 9	190.9 runs/min
Iteration 10	190.4 runs/min


#### JetStream raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-21
Score: 180.385

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit)
2023-12-21
Score: 180.141

Microsoft Edge v.120.0.2210.89 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-21
Score: 174.439

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
2023-12-21
Score: 176.882

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit)
2023-12-21
Score: 165.990

Mozilla Firefox v.121.0 (64-bit)
2023-12-21
Score: 129.801

GNOME Web/Epiphany v.45.1
2023-12-21
Score: 175.833


#### MotionMark raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-21
Score: 2419.74 ± 3.03%

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (64-bit)
2023-12-21
Score: 964.59 ± 2.67%

Microsoft Edge v.120.0.2210.89 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-21
Score: 842.76 ± 5.47%

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
2023-12-21
Score: 986.92 ± 2.87%

Ungoogled Chromium v.120.0.6099.129 (Official Build, ungoogled-chromium) (64-bit)
2023-12-21
Score: 848.31 ± 2.37%

Mozilla Firefox v.121.0 (64-bit)
2023-12-21
Score: 955.36 ± 2.76%

GNOME Web/Epiphany v.45.1
2023-12-21
Score: 259.37 ± 2.31%

-->