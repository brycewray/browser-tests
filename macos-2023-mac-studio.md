# Web browser tests on macOS

## OS, system, and testing specs

- macOS Sonoma v.14.2
- Mac Studio (mid-2023 version)
  - M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64 GB RAM
  - Internal graphics running 5120 × 2880 at 2x (“Retina”)
- Each browser running in private window; disabled extensions and tracking protection

----

## Jetstream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|--:|
| 1. | - | Orion | 0.99.126.4-beta (WebKit 618.1.2) | - | 364.465 | 2023-12-12 |
| 2. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 357.901 | 2023-12-12 |
| 3. | 1. | Brave | 1.61.101 | 120.0.6099.71 | 356.283 | 2023-12-12 |
| 4. | 2. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 353.843 | 2023-12-12 |
| 5. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 352.909 | 2023-12-12 |
| 6. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 351.304 | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 337.223 | 2023-12-12 |
| 8. | - | Mozilla Firefox | 120.0.1 | - | 236.867 | 2023-12-12 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 4612.97 ± 12.79% | 2023-12-12 |
| 2. | 2. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 4546.73 ± 14.47% | 2023-12-12 |
| 3. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 4496.01 ± 27.22% | 2023-12-12 |
| 4. | 4. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 4467.11 ± 13.73% | 2023-12-12 |
| 5. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 4365.06 ± 31.82% | 2023-12-12 |
| 6. | - | Orion | 0.99.126.4-beta (WebKit 618.1.2) | - | 3795.36 ± 22.80% | 2023-12-12 |
| 7. | 5. | Brave | 1.61.101 | 120.0.6099.71 | 3730.66 ± 26.15% | 2023-12-12 |
| 8. | - | Mozilla Firefox | 120.0.1 | - | 1777.31 ± 4.87% | 2023-12-12 |

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 490 ± 25 (5.0%) | 2023-12-12 |
| 2. | 1. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 443 ± 24 (5.3%) | 2023-12-12 |
| 3. | - | Mozilla Firefox | 120.0.1 | - | 436 ± 26 (6.0%) | 2023-12-12 |
| 4. | 2. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 423 ± 23 (5.4%) | 2023-12-12 |
| 5. | 3. | Brave | 1.61.101 | 120.0.6099.71 | 415 ± 16 (3.9%) | 2023-12-12 |
| 6. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 408 ± 25 (6.2%) | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 401 ± 18 (4.4%) | 2023-12-12 |
| 8. | - | Orion | 0.99.126.4-beta (WebKit 618.1.2) | - | 332 ± 28 (8.3%) | 2023-12-12 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Runs/<br>min. | Date |
|:--|:--|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 515.7 | 2023-12-12 |
| 2. | - | Mozilla Firefox | 120.0.1 | - | 457.8 | 2023-12-12 |
| 3. | 1. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 449.2 | 2023-12-12 |
| 4. | 2. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 446.8 | 2023-12-12 |
| 5. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 439.2 | 2023-12-12 |
| 6. | 4. | Brave | 1.61.101 | 120.0.6099.71 | 430.4 | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 417.7 | 2023-12-12 |
| 8. | - | Orion | 0.99.126.4-beta (WebKit 618.1.2) | - | 391.4 | 2023-12-12 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chr.<br>version | Runs/<br>min. | Date |
|:--|:--|:--|:-:|:-:|:-:|--:|
| 1. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 394.5 | 2023-12-12 |
| 2. | 1. | Vivaldi | 6.4.3160.47 | 118.0.5993.161 | 354.6 | 2023-12-12 |
| 3. | 2. | Brave | 1.61.101 | 120.0.6099.71 | 354.0 | 2023-12-12 |
| 4. | 3. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 339.7 | 2023-12-12 |
| T5. | - | Mozilla Firefox | 120.0.1 | - | 334.4 | 2023-12-12 |
| T5. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 334.4 | 2023-12-12 |
| 6. | - | Orion | 0.99.126.4-beta (WebKit 618.1.2) | - | 334.2 | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 332.7 | 2023-12-12 |

----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### JetStream raw data

Google Chrome v.120.0.6099.71 (Official Build) (arm64)
2023-12-12
Score: 337.223

Brave v.1.61.101 Chromium: 120.0.6099.71 (Official Build) (arm64)
2023-12-12
Score: 356.283

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-12
Score: 236.867

Safari v.17.1.2 (19616.2.9.11.12)
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

Google Chrome v.120.0.6099.71 (Official Build) (arm64)
2023-12-12
Score: 4612.97 ± 12.79%

Brave v.1.61.101 Chromium: 120.0.6099.71 (Official Build) (arm64)
2023-12-12
Score: 3730.66 ± 26.15%

Mozilla Firefox v.120.0.1 (64-bit)
2023-12-12
Score: 1777.31 ± 4.87%

Safari v.17.1.2 (19616.2.9.11.12)
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

Google Chrome v.120.0.6099.71 (Official Build) (arm64)
2023-12-12
Arithmetic Mean: 401 ± 18 (4.4%)
Iteration 1	332.7 runs/min  <-- WORST
Iteration 2	398.3 runs/min
Iteration 3	406.3 runs/min
Iteration 4	405.3 runs/min
Iteration 5	410.4 runs/min
Iteration 6	417.7 runs/min  <-- BEST
Iteration 7	399.8 runs/min
Iteration 8	407.8 runs/min
Iteration 9	415.4 runs/min
Iteration 10	413.4 runs/min

Brave v.1.61.101 Chromium: 120.0.6099.71 (Official Build) (arm64)
2023-12-12
Arithmetic Mean: 415 ± 16 (3.9%)
Iteration 1	354.0 runs/min  <-- WORST
Iteration 2	425.4 runs/min
Iteration 3	412.9 runs/min
Iteration 4	430.4 runs/min  <-- BEST
Iteration 5	428.1 runs/min
Iteration 6	411.8 runs/min
Iteration 7	419.3 runs/min
Iteration 8	409.4 runs/min
Iteration 9	430.3 runs/min
Iteration 10	426.6 runs/min

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

Safari v.17.1.2 (19616.2.9.11.12)
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
