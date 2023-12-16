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

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 214 ± 8.0 (3.7%) | 2023-12-16 |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 206 ± 5.8 (2.8%) | 2023-12-16 |
| 3. | 3. | Google Chrome | Google | 120.0.6099.109 | 120.0.6099.109 | 206 ± 7.6 (3.7%) | 2023-12-16 |
| 4. | &mdash; | Mozilla Firefox | Fedora | 120.0.1 | &mdash; | 199 ± 9.1 (4.6%) | 2023-12-16 |
| 5. | &mdash; | GNOME Web/Epiphany | Fedora | 45.1 | &mdash; | 183 ± 2.6 (1.4%) | 2023-12-16 |
| 6. | 4. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 169 ± 4.8 (2.9%) | 2023-12-16 |
| 7. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 166 ± 4.7 (2.9%) | 2023-12-16 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 225.4 | 2023-12-16 |
| 2. | 2. | Google Chrome | Google | 120.0.6099.109 | 120.0.6099.109 | 219.7 | 2023-12-16 |
| 3. | 3. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 215.7 | 2023-12-16 |
| 4. | &mdash; | Mozilla Firefox | Fedora | 120.0.1 | &mdash; | 210.8 | 2023-12-16 |
| 5. | &mdash; | GNOME Web/Epiphany | Fedora | 45.1 | &mdash; | 188.5 | 2023-12-16 |
| 6. | 4. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110  | 175.7 | 2023-12-16 |
| 7. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 173.9 | 2023-12-16 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 193.8 | 2023-12-16  |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 187.6 | 2023-12-16 |
| 3. | 3. | Google Chrome | Google | 120.0.6099.109 | 120.0.6099.109 | 180.2 | 2023-12-16 |
| 4. | &mdash; | GNOME Web/Epiphany | Fedora | 45.1 | &mdash; | 178.4 | 2023-12-16 |
| 5. | &mdash; | Mozilla Firefox | Fedora | 120.0.1 | &mdash; | 166.5 | 2023-12-16 |
| 6. | 4. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 151.8 | 2023-12-16 |
| 7. | 5. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110  | 151.3 | 2023-12-16 |

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.109 | 120.0.6099.109 | 177.602 | 2023-12-16 |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 176.918 | 2023-12-16 |
| 3. | 3. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 176.908 | 2023-12-16 |
| 4. | 4. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 174.280 | 2023-12-16 |
| 5. | 5. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 169.020 | 2023-12-16 |
| 6. | &mdash; | Mozilla Firefox | Fedora | 120.0.1 | &mdash; | 128.921 | 2023-12-16 |
| 7. | &mdash; | GNOME Web/Epiphany | Fedora | 45.1 | &mdash; | N/A[^DNF] | 2023-12-16 |

[^DNF]: Browser was unable to run this benchmark.

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Repo | Version | Chromium<br>version | Score | Date |
|--:|--:|:-:|:-:|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | Google | 120.0.6099.109 | 120.0.6099.109 | 2395.40 ± 2.84%[^real] | 2023-12-16 |
| 2. | 2. | Brave | Brave | 1.61.104 | 120.0.6099.115 | 979.03 ± 2.69% | 2023-12-16 |
| 3. | 3. | Vivaldi | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 961.43 ± 2.54% | 2023-12-16 |
| 4. | 4. | Ungoogled Chromium | Flathub | 119.0.6099.109 | 119.0.6099.109 | 852.85 ± 7.82% | 2023-12-16 |
| 5. | 5. | Microsoft Edge | Microsoft | 120.0.2210.77 | 120.0.6099.110 | 843.80 ± 4.70% | 2023-12-16 |
| 6. | &mdash; | GNOME Web/Epiphany | Fedora | 45.1 | &mdash; | 262.30 ± 17.24% | 2023-12-16 |
| 7. | &mdash; | Mozilla Firefox | Fedora | 120.0.1 | &mdash; | 224.02 ± 10.22% | 2023-12-16 |

[^real]: Not a typo; re-ran test on multiple browsers to confirm Chrome was this far ahead.

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-16
Arithmetic Mean: 206 ± 7.6 (3.7%)
Iteration 1	180.2 runs/min  <-- WORST
Iteration 2	206.2 runs/min
Iteration 3	199.6 runs/min
Iteration 4	213.3 runs/min
Iteration 5	206.5 runs/min
Iteration 6	203.6 runs/min
Iteration 7	219.7 runs/min  <-- BEST
Iteration 8	207.8 runs/min
Iteration 9	213.8 runs/min
Iteration 10	209.1 runs/min

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (64-bit)
2023-12-16
Arithmetic Mean: 206 ± 5.8 (2.8%)
Iteration 1	187.6 runs/min  <-- WORST
Iteration 2	201.4 runs/min
Iteration 3	201.4 runs/min
Iteration 4	203.1 runs/min
Iteration 5	209.6 runs/min
Iteration 6	215.7 runs/min  <-- BEST
Iteration 7	214.0 runs/min
Iteration 8	209.5 runs/min
Iteration 9	209.0 runs/min
Iteration 10	207.2 runs/min

Microsoft Edge v.120.0.2210.77 (Official build) (64-bit)
Chromium v.120.0.6099.110
2023-12-16
Arithmetic Mean: 169 ± 4.8 (2.9%)
Iteration 1	151.3 runs/min  <-- WORST
Iteration 2	169.8 runs/min
Iteration 3	170.2 runs/min
Iteration 4	170.8 runs/min
Iteration 5	167.2 runs/min
Iteration 6	175.7 runs/min  <-- BEST
Iteration 7	174.7 runs/min
Iteration 8	170.6 runs/min
Iteration 9	168.3 runs/min
Iteration 10	171.8 runs/min

Vivaldi v.6.5.3206.39 (Stable channel) stable (64-bit)
Chromium v.120.0.6099.121
2023-12-16
Arithmetic Mean: 214 ± 8.0 (3.7%)
Iteration 1	193.8 runs/min  <-- WORST
Iteration 2	207.8 runs/min
Iteration 3	209.0 runs/min
Iteration 4	224.9 runs/min
Iteration 5	203.6 runs/min
Iteration 6	209.6 runs/min
Iteration 7	224.8 runs/min
Iteration 8	225.4 runs/min  <-- BEST
Iteration 9	222.2 runs/min
Iteration 10	223.4 runs/min

Ungoogled Chromium v.120.0.6099.109 (Official Build, ungoogled-chromium) (64-bit)
2023-12-16
Arithmetic Mean: 166 ± 4.7 (2.9%)
Iteration 1	151.8 runs/min  <-- WORST
Iteration 2	166.0 runs/min
Iteration 3	165.9 runs/min
Iteration 4	168.5 runs/min
Iteration 5	173.9 runs/min  <-- BEST
Iteration 6	172.2 runs/min
Iteration 7	170.7 runs/min
Iteration 8	168.9 runs/min
Iteration 9	159.8 runs/min
Iteration 10	161.4 runs/min

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-16
Arithmetic Mean: 199 ± 9.1 (4.6%)
Iteration 1	166.5 runs/min  <-- WORST
Iteration 2	204.8 runs/min
Iteration 3	210.8 runs/min  <-- BEST
Iteration 4	201.4 runs/min
Iteration 5	199.0 runs/min
Iteration 6	203.1 runs/min
Iteration 7	201.3 runs/min
Iteration 8	189.8 runs/min
Iteration 9	208.5 runs/min
Iteration 10	203.2 runs/min

GNOME Web/Epiphany v.45.1
2023-12-16
Arithmetic Mean: 183 ± 2.6 (1.4%)
Iteration 1	184.1 runs/min
Iteration 2	179.1 runs/min
Iteration 3	186.4 runs/min
Iteration 4	185.8 runs/min
Iteration 5	179.3 runs/min
Iteration 6	186.9 runs/min
Iteration 7	182.4 runs/min
Iteration 8	178.4 runs/min  <-- WORST
Iteration 9	183.1 runs/min
Iteration 10	188.5 runs/min  <-- BEST


#### JetStream raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-16
Score: 177.602

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

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-16
Score: 128.921

GNOME Web/Epiphany v.45.1
2023-12-16
Score: N/A (hung on the first test and wouldn't proceed)

#### MotionMark raw data

Google Chrome v.120.0.6099.109 (Official Build) unknown (64-bit)
2023-12-16
Score: 2395.40 ± 2.84%

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

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-16
Score: 224.02 ± 10.22%

GNOME Web/Epiphany v.45.1
2023-12-16
Score: 262.30 ± 17.24%

-->