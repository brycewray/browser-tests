# Web browser tests on Fedora

## OS, system, and testing specs

- Fedora Linux 39 (Workstation Edition)
  - Firmware v.515.0.0.0.0
  - Kernel: Linux 6.6.6-200.fc39.x86_64
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
| 1. | 1. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 214 ± 8.0 (3.7%) | 2023-12-16 |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 206 ± 5.8 (2.8%) | 2023-12-16 |
| 3. | 3. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 203 ± 7.8 (3.9%) | 2023-12-20 |
| 4. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 199 ± 9.1 (4.6%) | 2023-12-19 |
| 5. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 183 ± 5.9 (3.2%) | 2023-12-19 |
| 6. | 4. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 169 ± 4.8 (2.9%) | 2023-12-16 |
| 7. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 166 ± 4.7 (2.9%) | 2023-12-16 |

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 180.865 | 2023-12-20 |
| 2. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 177.250 | 2023-12-19 |
| 3. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 176.918 | 2023-12-16 |
| 4. | 3. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 176.908 | 2023-12-16 |
| 5. | 4. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 174.280 | 2023-12-16 |
| 6. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 169.020 | 2023-12-16 |
| 7. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 128.921 | 2023-12-19 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.129 | 120.0.6099.129 | 2460.81 ± 2.97%[^real] | 2023-12-20 |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 979.03 ± 2.69% | 2023-12-16 |
| 3. | 3. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 961.43 ± 2.54% | 2023-12-16 |
| 4. | 4. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 852.85 ± 7.82% | 2023-12-16 |
| 5. | 5. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 843.80 ± 4.70% | 2023-12-16 |
| 6. | &mdash; | GNOME Web/Epiphany | Flathub | 45.1 | &mdash; | 249.44 ± 8.08% | 2023-12-19 |
| 7. | &mdash; | Mozilla Firefox | Flathub | 121.0 | &mdash; | 224.02 ± 10.22% | 2023-12-19 |

[^real]: Not a typo.

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-20
Arithmetic Mean: 203 ± 7.8 (3.9%)
Iteration 1	179.1 runs/min
Iteration 2	198.6 runs/min
Iteration 3	208.3 runs/min
Iteration 4	215.9 runs/min
Iteration 5	214.3 runs/min
Iteration 6	202.7 runs/min
Iteration 7	206.1 runs/min
Iteration 8	211.0 runs/min
Iteration 9	205.4 runs/min
Iteration 10	193.4 runs/min

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (64-bit)
2023-12-16
Arithmetic Mean: 206 ± 5.8 (2.8%)
Iteration 1	187.6 runs/min
Iteration 2	201.4 runs/min
Iteration 3	201.4 runs/min
Iteration 4	203.1 runs/min
Iteration 5	209.6 runs/min
Iteration 6	215.7 runs/min
Iteration 7	214.0 runs/min
Iteration 8	209.5 runs/min
Iteration 9	209.0 runs/min
Iteration 10	207.2 runs/min

Microsoft Edge v.120.0.2210.77 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-16
Arithmetic Mean: 169 ± 4.8 (2.9%)
Iteration 1	151.3 runs/min
Iteration 2	169.8 runs/min
Iteration 3	170.2 runs/min
Iteration 4	170.8 runs/min
Iteration 5	167.2 runs/min
Iteration 6	175.7 runs/min
Iteration 7	174.7 runs/min
Iteration 8	170.6 runs/min
Iteration 9	168.3 runs/min
Iteration 10	171.8 runs/min

Vivaldi v.6.5.3206.39 (Stable channel) stable (64-bit)
Chromium v.120.0.6099.121
2023-12-16
Arithmetic Mean: 214 ± 8.0 (3.7%)
Iteration 1	193.8 runs/min
Iteration 2	207.8 runs/min
Iteration 3	209.0 runs/min
Iteration 4	224.9 runs/min
Iteration 5	203.6 runs/min
Iteration 6	209.6 runs/min
Iteration 7	224.8 runs/min
Iteration 8	225.4 runs/min
Iteration 9	222.2 runs/min
Iteration 10	223.4 runs/min

Ungoogled Chromium v.120.0.6099.109 (Official Build, ungoogled-chromium) (64-bit)
2023-12-16
Arithmetic Mean: 166 ± 4.7 (2.9%)
Iteration 1	151.8 runs/min
Iteration 2	166.0 runs/min
Iteration 3	165.9 runs/min
Iteration 4	168.5 runs/min
Iteration 5	173.9 runs/min
Iteration 6	172.2 runs/min
Iteration 7	170.7 runs/min
Iteration 8	168.9 runs/min
Iteration 9	159.8 runs/min
Iteration 10	161.4 runs/min

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Arithmetic Mean: 215 ± 11 (5.3%)
Iteration 1	175.0 runs/min
Iteration 2	221.9 runs/min
Iteration 3	225.0 runs/min
Iteration 4	219.5 runs/min
Iteration 5	201.6 runs/min
Iteration 6	219.4 runs/min
Iteration 7	228.2 runs/min
Iteration 8	218.1 runs/min
Iteration 9	211.2 runs/min
Iteration 10	225.3 runs/min

GNOME Web/Epiphany v.45.1
2023-12-19
Arithmetic Mean: 183 ± 5.9 (3.2%)
Iteration 1	162.6 runs/min
Iteration 2	181.2 runs/min
Iteration 3	187.1 runs/min
Iteration 4	185.1 runs/min
Iteration 5	190.7 runs/min
Iteration 6	188.5 runs/min
Iteration 7	187.5 runs/min
Iteration 8	186.7 runs/min
Iteration 9	183.2 runs/min
Iteration 10	176.7 runs/min


#### JetStream raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-20
Score: 180.865

Brave v.1.61.104 with Chromium: 120.0.6099.115 (Official Build) unknown (64-bit)
2023-12-16
Score: 176.918

Microsoft Edge v.120.0.2210.77 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-16
Score: 174.280

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
2023-12-16
Score: 176.908

Ungoogled Chromium v.120.0.6099.109 (Official Build, ungoogled-chromium) (64-bit)
2023-12-16
Score: 169.020

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 136.720

GNOME Web/Epiphany v.45.1
2023-12-19
Score: 177.250

#### MotionMark raw data

Google Chrome v.120.0.6099.129 (Official Build) unknown (64-bit)
2023-12-20
Score: 2460.81 ± 2.97%

Brave v.1.61.104 with Chromium: 120.0.6099.115 (Official Build) unknown (64-bit)
2023-12-16
Score: 979.03 ± 2.69%

Microsoft Edge v.120.0.2210.77 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-16
Score: 843.80 ± 4.70%

Vivaldi v.6.5.3206.39 (Stable channel) (64-bit)
Chromium v.120.0.6099.121
2023-12-16
Score: 961.43 ± 2.54%

Ungoogled Chromium v.120.0.6099.109 (Official Build, ungoogled-chromium) (64-bit)
2023-12-16
Score: 852.85 ± 7.82%

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 935.91 ± 9.37%

GNOME Web/Epiphany v.45.1
2023-12-19
Score: 249.44 ± 8.08%

-->