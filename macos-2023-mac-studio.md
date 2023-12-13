# Web browser tests on macOS

## OS, system, and testing specs

- macOS Sonoma v.14.2
- Mac Studio (mid-2023 version)
  - M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64 GB RAM
  - Internal graphics running 5120 × 2880 at 2x (“Retina”)
- Each browser running in private window; disabled extensions and tracking protection

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | - | Orion | 0.99.126.4-beta<br>(WebKit 618.1.2) | - | 364.465 | 2023-12-12 |
| 2. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 361.499 | 2023-12-13 |
| 3. | - | Safari | 17.2<br>(19617.1.17.11.9) | - | 357.901 | 2023-12-12 |
| 4. | 2. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 353.843 | 2023-12-12 |
| 5. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 352.909 | 2023-12-12 |
| 6. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 351.304 | 2023-12-12 |
| 7. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 341.232 | 2023-12-13 |
| 8. | - | Mozilla Firefox | 120.0.1 | - | 236.867 | 2023-12-12 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 4642.71 ± 14.80% | 2023-12-13 |
| 2. | 2. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 4546.73 ± 14.47% | 2023-12-12 |
| 3. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 4496.01 ± 27.22% | 2023-12-12 |
| 4. | 4. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 4467.11 ± 13.73% | 2023-12-12 |
| 5. | - | Safari | 17.2<br>(19617.1.17.11.9) | - | 4365.06 ± 31.82% | 2023-12-12 |
| 6. | - | Orion | 0.99.126.4-beta<br>(WebKit 618.1.2) | - | 3795.36 ± 22.80% | 2023-12-12 |
| 7. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 3657.34 ± 22.13% | 2023-12-13 |
| 8. | - | Mozilla Firefox | 120.0.1 | - | 1777.31 ± 4.87% | 2023-12-12 |

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.2<br>(19617.1.17.11.9) | - | 490 ± 25 (5.0%) | 2023-12-12 |
| 2. | 1. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 443 ± 24 (5.3%) | 2023-12-12 |
| 3. | - | Mozilla Firefox | 120.0.1 | - | 436 ± 26 (6.0%) | 2023-12-12 |
| 4. | 2. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 423 ± 23 (5.4%) | 2023-12-12 |
| 5. | 3. | Brave | 1.61.104 | 120.0.6099.115 | 410 ± 18 (4.5%) | 2023-12-13 |
| 6. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 408 ± 25 (6.2%) | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 403 ± 16 (4.0%) | 2023-12-13 |
| 8. | - | Orion | 0.99.126.4-beta<br>(WebKit 618.1.2) | - | 332 ± 28 (8.3%) | 2023-12-12 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.2<br>(19617.1.17.11.9) | - | 515.7 | 2023-12-12 |
| 2. | - | Mozilla Firefox | 120.0.1 | - | 457.8 | 2023-12-12 |
| 3. | 1. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 449.2 | 2023-12-12 |
| 4. | 2. | Brave | 1.61.104 | 120.0.6099.115 | 447.7 | 2023-12-13 |
| 5. | 3. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 446.8 | 2023-12-12 |
| 6. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 439.2 | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 415.7 | 2023-12-13 |
| 8. | - | Orion | 0.99.126.4-beta<br>(WebKit 618.1.2) | - | 391.4 | 2023-12-12 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.2<br>(19617.1.17.11.9) | - | 394.5 | 2023-12-12 |
| 2. | 1. | Brave | 1.61.104 | 120.0.6099.115 | 361.0 | 2023-12-13 |
| 3. | 2. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 354.6 | 2023-12-12 |
| 4. | 3. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 341.7 | 2023-12-13 |
| 5. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 339.7 | 2023-12-12 |
| T6. | 5. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 334.4 | 2023-12-12 |
| T6. | - | Mozilla Firefox | 120.0.1 | - | 334.4 | 2023-12-12 |
| 8. | - | Orion | 0.99.126.4-beta<br>(WebKit 618.1.2) | - | 334.2 | 2023-12-12 |

----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### JetStream raw data

Google Chrome v.120.0.6099.109 (Official Build) (arm64)
2023-12-13
Score: 361.499

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-13
Score: 341.232

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-12
Score: 236.867

Safari v.17.2 (19617.1.17.11.9)
2023-12-12
Score: 357.901

Microsoft Edge v.120.0.2210.61 (Official build) (arm64)
Chromium v.120.0.6099.71
2023-12-12
Score: 351.304

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.56 (Official Build) (arm64)
2023-12-12
Score: 352.909

Orion v.0.99.126.4-beta (WebKit 618.1.2)
2023-12-12
Score: 364.465

Vivaldi v.6.4.3160.47 (Stable channel) (arm64)
Chromium v.118.0.5993.161
2023-12-12
Score: 353.843

#### MotionMark raw data

Google Chrome v.120.0.6099.109 (Official Build) (arm64)
2023-12-13
Score: 4642.71 ± 14.80%

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-13
Score: 3657.34 ± 22.13%

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-12
Score: 1777.31 ± 4.87%

Safari v.17.2 (19617.1.17.11.9)
2023-12-12
Score: 4365.06 ± 31.82%

Microsoft Edge v.120.0.2210.61 (Official build) (arm64)
Chromium v.120.0.6099.71
2023-12-12
Score: 4496.01 ± 27.22%

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.56 (Official Build) (arm64)
2023-12-12
Score: 4546.73 ± 14.47%

Orion v.0.99.126.4-beta (WebKit 618.1.2)
2023-12-12
Score: 3795.36 ± 22.80%

Vivaldi v.6.4.3160.47 (Stable channel) (arm64)
Chromium v.118.0.5993.161
2023-12-12
Score: 4467.11 ± 13.73%

#### Speedometer raw data

Google Chrome v.120.0.6099.109 (Official Build) (arm64)
2023-12-13
Arithmetic Mean: 403 ± 16 (4.0%)
Iteration 1	341.7 runs/min  <-- WORST
Iteration 2	393.8 runs/min
Iteration 3	411.1 runs/min
Iteration 4	414.4 runs/min
Iteration 5	413.4 runs/min
Iteration 6	415.3 runs/min
Iteration 7	414.8 runs/min
Iteration 8	415.7 runs/min  <-- BEST
Iteration 9	412.3 runs/min
Iteration 10	401.1 runs/min

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-13
Arithmetic Mean: 410 ± 18 (4.5%)
Iteration 1	361.0 runs/min  <-- WORST
Iteration 2	407.7 runs/min
Iteration 3	414.8 runs/min
Iteration 4	411.9 runs/min
Iteration 5	438.8 runs/min
Iteration 6	411.1 runs/min
Iteration 7	447.7 runs/min  <-- BEST
Iteration 8	423.5 runs/min
Iteration 9	411.8 runs/min
Iteration 10	376.4 runs/min

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-12
Arithmetic Mean: 436 ± 26 (6.0%)
Iteration 1	334.4 runs/min  <-- WORST
Iteration 2	441.9 runs/min
Iteration 3	448.2 runs/min
Iteration 4	457.8 runs/min  <-- BEST
Iteration 5	455.3 runs/min
Iteration 6	443.3 runs/min
Iteration 7	441.1 runs/min
Iteration 8	454.6 runs/min
Iteration 9	441.7 runs/min
Iteration 10	439.8 runs/min

Safari v.17.2 (19617.1.17.11.9)
2023-12-12
Arithmetic Mean: 490 ± 25 (5.0%)
Iteration 1	394.5 runs/min  <-- WORST
Iteration 2	490.2 runs/min
Iteration 3	494.4 runs/min
Iteration 4	491.1 runs/min
Iteration 5	497.8 runs/min
Iteration 6	504.6 runs/min
Iteration 7	495.7 runs/min
Iteration 8	503.2 runs/min
Iteration 9	508.4 runs/min
Iteration 10	515.7 runs/min  <-- BEST

Microsoft Edge v.120.0.2210.61 (Official build) (arm64)
Chromium v.120.0.6099.71
2023-12-12
Arithmetic Mean: 423 ± 23 (5.4%)
Iteration 1	339.7 runs/min  <-- WORST
Iteration 2	415.3 runs/min
Iteration 3	433.0 runs/min
Iteration 4	432.2 runs/min
Iteration 5	441.4 runs/min
Iteration 6	449.2 runs/min  <-- BEST
Iteration 7	414.6 runs/min
Iteration 8	430.7 runs/min
Iteration 9	428.9 runs/min
Iteration 10	449.1 runs/min

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.56 (Official Build) (arm64)
2023-12-12
Arithmetic Mean: 408 ± 25 (6.2%)
Iteration 1	334.4 runs/min  <-- WORST
Iteration 2	424.0 runs/min
Iteration 3	416.6 runs/min
Iteration 4	439.2 runs/min  <-- BEST
Iteration 5	426.9 runs/min
Iteration 6	418.8 runs/min
Iteration 7	349.9 runs/min
Iteration 8	419.2 runs/min
Iteration 9	432.5 runs/min
Iteration 10	419.0 runs/min

Orion v.0.99.126.4-beta (WebKit 618.1.2)
2023-12-12
Arithmetic Mean: 332 ± 28 (8.3%)
Iteration 1	309.9 runs/min
Iteration 2	385.9 runs/min
Iteration 3	352.4 runs/min
Iteration 4	342.7 runs/min
Iteration 5	316.8 runs/min
Iteration 6	311.0 runs/min
Iteration 7	305.9 runs/min
Iteration 8	391.4 runs/min  <-- BEST
Iteration 9	334.2 runs/min
Iteration 10	264.8 runs/min  <-- WORST

Vivaldi v.6.4.3160.47 (Stable channel) (arm64)
Chromium v.118.0.5993.161
2023-12-12
Arithmetic Mean: 443 ± 24 (5.3%)
Iteration 1	354.6 runs/min  <-- WORST
Iteration 2	453.3 runs/min
Iteration 3	445.2 runs/min
Iteration 4	430.4 runs/min
Iteration 5	457.6 runs/min
Iteration 6	446.8 runs/min  <-- BEST
Iteration 7	470.1 runs/min
Iteration 8	445.9 runs/min
Iteration 9	459.2 runs/min
Iteration 10	466.2 runs/min
