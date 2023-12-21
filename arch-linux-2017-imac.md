# Web browser tests on Arch Linux

> [!NOTE]
> I later decided to do my Linux testing in Fedora rather than Arch, due to the easier availability of truly official browser versions for that Linux distribution. The resulting page is [here](https://github.com/brycewray/browser-tests/blob/main/fedora-linux-2017-imac.md).

## OS, system, and testing specs

- Arch Linux
  - Firmware v.515.0.0.0.0
  - Kernel: Linux 6.6.7-arch1-1
  - GNOME 45.2 / Wayland
- iMac 18,3 (mid-2017 iMac)
  - Intel® Core™ i7-7700K × 8, 64GB RAM
  - AMD Radeon™ Pro 580X running 3840 × 2160 at 2x
- Each browser running in private window; disabled extensions and tracking protection
- Each browser via Flathub unless otherwise noted

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 201 ± 8.6 (4.3%) | 2023-12-14 |
| 2. | &mdash; | GNOME Web/Epiphany | 45.1 | &mdash; | 199 ± 7.4 (3.7%) | 2023-12-14 |
| 3. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 199 ± 8.5 (4.3%) | 2023-12-14 |
| 4. | 2. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 194 ± 6.4 (3.3%) | 2023-12-14 |
| 5. | 3. | Brave | 1.61.104 | 120.0.6099.109 | 185 ± 7.8 (4.2%) | 2023-12-14 |
| 6. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 166 ± 5.4 (3.2%) | 2023-12-14 |
| 7. | 5. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 157 ± 4.9 (3.1%) | 2023-12-14 |

[^UgC]: From the AUR as `ungoogled-chromium-bin`.

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 183.205 | 2023-12-14 |
| 2. | &mdash; | GNOME Web/Epiphany | 45.1 | &mdash; | 183.110 | 2023-12-14 |
| 3. | 2. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 182.391 | 2023-12-14 |
| 4. | 3. | Brave | 1.61.104 | 120.0.6099.109 | 180.530 | 2023-12-14 |
| 5. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 179.129 | 2023-12-14 |
| 6. | 5. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 175.108 | 2023-12-14 |
| 7. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 134.625 | 2023-12-14 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 998.71 ± 1.98% | 2023-12-14 |
| 2. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 984.94 ± 6.32% | 2023-12-14 |
| 3. | 3. | Brave | 1.61.104 | 120.0.6099.109 | 957.88 ± 9.12% | 2023-12-14 |
| 4. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 946.89 ± 8.67% | 2023-12-14 |
| 5. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 828.42 ± 4.86% | 2023-12-14 |
| 6. | 5. | Ungoogled Chromium[^UgC] | 119.0.6045.199 | 119.0.6045.199 | 819.83 ± 2.71% | 2023-12-14 |
| 7. | &mdash; | GNOME Web/Epiphany | 45.1 | &mdash; | 228.86 ± 25.23% | 2023-12-14 |

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-14
Arithmetic Mean: 194 ± 6.4 (3.3%)
Iteration 1	175.6 runs/min  <-- WORST
Iteration 2	193.8 runs/min
Iteration 3	195.2 runs/min
Iteration 4	206.8 runs/min  <-- BEST
Iteration 5	186.9 runs/min
Iteration 6	201.1 runs/min
Iteration 7	198.5 runs/min
Iteration 8	200.5 runs/min
Iteration 9	187.4 runs/min
Iteration 10	195.0 runs/min

Brave v.1.61.104 with Chromium: 120.0.6099.115 (Official Build) unknown (64-bit)
2023-12-14
Arithmetic Mean: 185 ± 7.8 (4.2%)
Iteration 1	161.8 runs/min  <-- WORST
Iteration 2	186.5 runs/min
Iteration 3	195.1 runs/min
Iteration 4	186.8 runs/min
Iteration 5	197.0 runs/min  <-- BEST
Iteration 6	180.3 runs/min
Iteration 7	193.9 runs/min
Iteration 8	178.8 runs/min
Iteration 9	195.3 runs/min
Iteration 10	179.3 runs/min

Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
Chromium v.120.0.6099.71
2023-12-14
Arithmetic Mean: 166 ± 5.4 (3.2%)
Iteration 1	147.6 runs/min  <-- WORST
Iteration 2	165.7 runs/min
Iteration 3	164.7 runs/min
Iteration 4	171.1 runs/min
Iteration 5	176.4 runs/min  <-- BEST
Iteration 6	166.5 runs/min
Iteration 7	163.0 runs/min
Iteration 8	168.9 runs/min
Iteration 9	169.6 runs/min
Iteration 10	165.8 runs/min

Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-08
Arithmetic Mean: 157 ± 4.9 (3.1%)
Iteration 1	148.7 runs/min
Iteration 2	150.1 runs/min
Iteration 3	159.5 runs/min
Iteration 4	155.5 runs/min
Iteration 5	153.4 runs/min
Iteration 6	159.1 runs/min
Iteration 7	170.0 runs/min  <-- BEST
Iteration 8	163.0 runs/min
Iteration 9	148.5 runs/min  <-- WORST
Iteration 10	158.7 runs/min

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-14
Arithmetic Mean: 201 ± 8.6 (4.3%)
Iteration 1	170.4 runs/min  <-- WORST
Iteration 2	204.2 runs/min
Iteration 3	205.0 runs/min
Iteration 4	209.7 runs/min
Iteration 5	203.0 runs/min
Iteration 6	209.9 runs/min
Iteration 7	205.8 runs/min
Iteration 8	212.7 runs/min  <-- BEST
Iteration 9	198.4 runs/min
Iteration 10	195.8 runs/min

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
Arithmetic Mean: 199 ± 8.5 (4.3%)
Iteration 1	181.9 runs/min
Iteration 2	181.1 runs/min  <-- WORST
Iteration 3	204.5 runs/min
Iteration 4	200.1 runs/min
Iteration 5	204.8 runs/min
Iteration 6	217.0 runs/min  <-- BEST
Iteration 7	201.9 runs/min
Iteration 8	194.5 runs/min
Iteration 9	193.6 runs/min
Iteration 10	214.0 runs/min

GNOME Web/Epiphany v.45.1
Arithmetic Mean: 199 ± 7.4 (3.7%)
Iteration 1	172.5 runs/min  <-- WORST
Iteration 2	197.6 runs/min
Iteration 3	205.2 runs/min
Iteration 4	202.2 runs/min
Iteration 5	204.2 runs/min
Iteration 6	205.0 runs/min
Iteration 7	203.6 runs/min
Iteration 8	206.8 runs/min  <-- BEST
Iteration 9	202.1 runs/min
Iteration 10	192.1 runs/min

#### JetStream raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-14
Score: 182.391

Brave v.1.61.104 with Chromium: 120.0.6099.115 (Official Build) unknown (64-bit)
2023-12-14
Score: 180.530

Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
Chromium v.120.0.6099.71
2023-12-14
Score: 179.129

Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-14
Score: 175.108

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-14
Score: 134.625

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
Score: 183.205

GNOME Web/Epiphany v.45.1
Score: 183.110

#### MotionMark raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-14
Score: 998.71 ± 1.98%

Brave v.1.61.104 with Chromium: 120.0.6099.115 (Official Build) unknown (64-bit)
2023-12-14
Score: 957.88 ± 9.12%

Microsoft Edge v.120.0.2210.61 (Official build) (64-bit)
Chromium v.120.0.6099.71
2023-12-14
Score: 828.42 ± 4.86%

Ungoogled Chromium v.119.0.6045.199 (Official Build, ungoogled-chromium) Arch Linux (64-bit)
via AUR (`ungoogled-chromium-bin`)
2023-12-08
Score: 819.83 ± 2.71%

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-14
Score: 946.89 ± 8.67%

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
Score: 984.94 ± 6.32%

GNOME Web/Epiphany v.45.1
Score: 228.86 ± 25.23%
("Leaves" = 90.00 ± 302.74% - !?!)

-->