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
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 361.499 | 2023-12-13 |
| 2. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 357.901 | 2023-12-12 |
| 3. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 356.565 | 2023-12-14 |
| 4. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 355.110 | 2023-12-14 |
| 5. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 352.909 | 2023-12-12 |
| 6. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 351.304 | 2023-12-12 |
| 7. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 341.232 | 2023-12-13 |
| 8. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 236.867 | 2023-12-12 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 4642.71 ± 14.80% | 2023-12-13 |
| 2. | 2. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 4546.73 ± 14.47% | 2023-12-12 |
| 3. | 3. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 4519.09 ± 18.93% | 2023-12-14 |
| 4. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 4496.01 ± 27.22% | 2023-12-12 |
| 5. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 4365.06 ± 31.82% | 2023-12-12 |
| 6. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 3657.34 ± 22.13% | 2023-12-13 |
| 7. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 3653.62 ± 5.89% | 2023-12-14 |
| 8. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 1777.31 ± 4.87% | 2023-12-12 |

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 490 ± 25 (5.0%) | 2023-12-12 |
| 2. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 436 ± 26 (6.0%) | 2023-12-12 |
| 3. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 435 ± 22 (5.2%) | 2023-12-14 |
| 4. | 2. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 423 ± 23 (5.4%) | 2023-12-12 |
| 5. | 3. | Brave | 1.61.104 | 120.0.6099.115 | 410 ± 18 (4.5%) | 2023-12-13 |
| 6. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 408 ± 25 (6.2%) | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 403 ± 16 (4.0%) | 2023-12-13 |
| 8. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 309 ± 31 (10%) | 2023-12-14 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 515.7 | 2023-12-12 |
| 2. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 457.8 | 2023-12-12 |
| 3. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 455.0 | 2023-12-14 |
| 4. | 2. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 449.2 | 2023-12-12 |
| 5. | 3. | Brave | 1.61.104 | 120.0.6099.115 | 447.7 | 2023-12-13 |
| 6. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 439.2 | 2023-12-12 |
| 7. | 5. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 415.7 | 2023-12-13 |
| 8. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 403.5 | 2023-12-14 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 394.5 | 2023-12-12 |
| 2. | 1. | Brave | 1.61.104 | 120.0.6099.115 | 361.0 | 2023-12-13 |
| 3. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 347.7 | 2023-12-14 |
| 4. | 3. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 341.7 | 2023-12-13 |
| 5. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 339.7 | 2023-12-12 |
| T6. | 5. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 334.4 | 2023-12-12 |
| T6. | &mdash; | Mozilla Firefox | 120.0.1 | &mdash; | 334.4 | 2023-12-12 |
| 8. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 245.8 | 2023-12-14 |

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

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-14
Score: 356.565

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-14
Score: 355.110

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

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-14
Score: 3653.62 ± 5.89%

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-14
Score: 4519.09 ± 18.93%

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

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-14
Arithmetic Mean: 309 ± 31 (10%)
Iteration 1	348.9 runs/min
Iteration 2	403.5 runs/min  <-- BEST
Iteration 3	291.9 runs/min
Iteration 4	306.1 runs/min
Iteration 5	294.5 runs/min
Iteration 6	290.3 runs/min
Iteration 7	315.9 runs/min
Iteration 8	322.0 runs/min
Iteration 9	269.7 runs/min
Iteration 10	245.8 runs/min  <-- WORST

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-14
Arithmetic Mean: 435 ± 22 (5.2%)
Iteration 1	347.7 runs/min  <-- WORST
Iteration 2	445.8 runs/min
Iteration 3	454.6 runs/min
Iteration 4	438.0 runs/min
Iteration 5	455.0 runs/min  <-- BEST
Iteration 6	441.7 runs/min
Iteration 7	448.0 runs/min
Iteration 8	434.4 runs/min
Iteration 9	441.3 runs/min
Iteration 10	442.9 runs/min
