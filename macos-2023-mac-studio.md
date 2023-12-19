# Web browser tests on macOS

## OS, system, and testing specs

- macOS Sonoma v.14.2
- Mac Studio (mid-2023 version)
  - M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64 GB RAM
  - Internal graphics running 5120 × 2880 at 2x (“Retina”)
- Each browser running in private window; disabled extensions and tracking protection

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 490 ± 25 (5.0%) | 2023-12-12 |
| 2. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 435 ± 22 (5.2%) | 2023-12-14 |
| 3. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 421 ± 27 (6.4%) | 2023-12-19 |
| 4. | 2. | Brave | 1.61.104 | 120.0.6099.115 | 410 ± 18 (4.5%) | 2023-12-13 |
| 5. | 3. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 403 ± 16 (4.0%) | 2023-12-13 |
| 6. | 4. | Arc | 1.21.1 (44274) | 120.0.6099.109 | 397 ± 15 (3.8%) | 2023-12-15 |
| 7. | 5. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 390 ± 16 (4.1%) | 2023-12-15 |
| 8. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 309 ± 31 (10%) | 2023-12-14 |

### By BEST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 515.7 | 2023-12-12 |
| 2. | 1. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 455.0 | 2023-12-14 |
| 3. | 2. | Brave | 1.61.104 | 120.0.6099.115 | 447.7 | 2023-12-13 |
| 4. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 444.1 | 2023-12-19 |
| 5. | 3. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 415.7 | 2023-12-13 |
| 6. | 4. | Arc | 1.21.1 (44274) | 120.0.6099.109 | 412.7 | 2023-12-15 |
| 7. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 403.5 | 2023-12-14 |
| 8. | 5. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 400.0 | 2023-12-15 |

### By WORST RESULT of 10 iterations

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Runs/<br>min. | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 394.5 | 2023-12-12 |
| 2. | 1. | Brave | 1.61.104 | 120.0.6099.115 | 361.0 | 2023-12-13 |
| 3. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 347.7 | 2023-12-14 |
| 4. | 3. | Arc | 1.21.1 (44274) | 120.0.6099.109 | 343.8 | 2023-12-15 |
| 5. | 4. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 341.7 | 2023-12-13 |
| 5. | 5. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 326.4 | 2023-12-15 |
| 7. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 314.7 | 2023-12-19 |
| 8. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 245.8 | 2023-12-14 |

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 361.499 | 2023-12-13 |
| 2. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 357.901 | 2023-12-12 |
| 3. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 356.565 | 2023-12-14 |
| 4. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 355.110 | 2023-12-14 |
| 5. | 3. | Arc | 1.21.1 (44274) | 120.0.6099.109 | 354.602 | 2023-12-15 |
| 6. | 4. | Brave | 1.61.104 | 120.0.6099.115 | 341.232 | 2023-12-13 |
| 7. | 5. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 334.443 | 2023-12-15 |
| 8. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 227.580 | 2023-12-19 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Google Chrome | 120.0.6099.109 | 120.0.6099.109 | 4642.71 ± 14.80% | 2023-12-13 |
| 2. | 2. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 4519.09 ± 18.93% | 2023-12-14 |
| 3. | &mdash; | Safari | 17.2<br>(19617.1.17.11.9) | &mdash; | 4365.06 ± 31.82% | 2023-12-12 |
| 4. | 3. | Arc | 1.21.1 (44274) | 120.0.6099.109 | 4363.96 ± 10.10% | 2023-12-15 |
| 5. | 4. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 4253.68 ± 25.98% | 2023-12-15 |
| 6. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 3657.34 ± 22.13% | 2023-12-13 |
| 7. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 3653.62 ± 5.89% | 2023-12-14 |
| 8. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 1536.32 ± 2.66% | 2023-12-19 |

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

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

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Arithmetic Mean: 421 ± 27 (6.4%)
Iteration 1	314.7 runs/min  <-- WORST
Iteration 2	423.2 runs/min
Iteration 3	444.1 runs/min  <-- BEST
Iteration 4	437.6 runs/min
Iteration 5	433.7 runs/min
Iteration 6	440.3 runs/min
Iteration 7	430.2 runs/min
Iteration 8	426.4 runs/min
Iteration 9	423.9 runs/min
Iteration 10	432.9 runs/min

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

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-15
Arithmetic Mean: 390 ± 16 (4.1%)
Iteration 1	326.4 runs/min  <-- WORST
Iteration 2	397.1 runs/min
Iteration 3	400.0 runs/min  <-- BEST
Iteration 4	396.0 runs/min
Iteration 5	391.5 runs/min
Iteration 6	398.1 runs/min
Iteration 7	399.0 runs/min
Iteration 8	395.6 runs/min
Iteration 9	398.9 runs/min
Iteration 10	394.3 runs/min

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-15
Arithmetic Mean: 397 ± 15 (3.8%)
Iteration 1	343.8 runs/min  <-- WORST
Iteration 2	398.2 runs/min
Iteration 3	400.4 runs/min
Iteration 4	380.0 runs/min
Iteration 5	412.5 runs/min
Iteration 6	412.7 runs/min  <-- BEST
Iteration 7	411.7 runs/min
Iteration 8	406.2 runs/min
Iteration 9	401.8 runs/min
Iteration 10	407.5 runs/min

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

#### JetStream raw data

Google Chrome v.120.0.6099.109 (Official Build) (arm64)
2023-12-13
Score: 361.499

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-13
Score: 341.232

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 227.580

Safari v.17.2 (19617.1.17.11.9)
2023-12-12
Score: 357.901

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-15
Score: 334.443

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-15
Score: 354.602

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

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 1536.32 ± 2.66%

Safari v.17.2 (19617.1.17.11.9)
2023-12-12
Score: 4365.06 ± 31.82%

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-15
Score: 4253.68 ± 25.98%

Arc v.1.20.1 (43987)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-15
Score: 4363.96 ± 10.10%

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-14
Score: 3653.62 ± 5.89%

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-14
Score: 4519.09 ± 18.93%

-->