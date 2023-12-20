# Web browser tests on macOS

## OS, system, and testing specs

- macOS Sonoma v.14.2.1
- Mac Studio (mid-2023 version)
  - M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64 GB RAM
  - Internal graphics running 5120 × 2880 at 2x (“Retina”)
- Each browser running in private window; disabled extensions and tracking protection

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2.1<br>(19617.1.17.11.12) | &mdash; | 478 ± 25 (5.2%) | 2023-12-19 |
| 2. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 455 ± 24 (5.2%) | 2023-12-19 |
| 3. | 1. | Google Chrome | 120.0.6099.129 | 120.0.6099.129 | 432 ± 16 (3.8%) | 2023-12-20 |
| 4. | 2. | Brave | 1.61.104 | 120.0.6099.115 | 425 ± 16 (3.7%) | 2023-12-19 |
| 5. | 3. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 425 ± 22 (5.3%) | 2023-12-19 |
| 6. | 4. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 424 ± 18 (4.3%) | 2023-12-19 |
| 7. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 416 ± 20 (4.8%) | 2023-12-19 |
| 8. | 5. | Arc | 1.21.1 (44329) | 120.0.6099.109 | 414 ± 17 (4.1%) | 2023-12-19 |

----

## JetStream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 17.2.1<br>(19617.1.17.11.12) | &mdash; | 360.445 | 2023-12-19 |
| 2. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 358.589 | 2023-12-19 |
| 3. | 1. | Arc | 1.21.1 (44329) | 120.0.6099.109 | 348.946 | 2023-12-19 |
| 4. | 2. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 346.891 | 2023-12-19 |
| 5. | 3. | Google Chrome | 120.0.6099.129 | 120.0.6099.129 | 341.568 | 2023-12-20 |
| 6. | 4. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 329.877 | 2023-12-19 |
| 7. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 324.771 | 2023-12-19 |
| 8. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 236.463 | 2023-12-19 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chr.<br>rank | Browser | Version | Chromium<br>version | Score | Date |
|--:|--:|:--|:-:|:-:|:-:|--:|
| 1. | 1. | Microsoft Edge | 120.0.2210.77 | 120.0.6099.110 | 4650.73 ± 17.15% | 2023-12-19 |
| 2. | 2. | Arc | 1.21.1 (44329) | 120.0.6099.109 | 4532.02 ± 19.92% | 2023-12-19 |
| 3. | 3. | Google Chrome | 120.0.6099.129 | 120.0.6099.129 | 4438.72 ± 14.42% | 2023-12-20 |
| 4. | 4. | Vivaldi | 6.5.3206.39 | 120.0.6099.121 | 4301.27 ± 14.11% | 2023-12-19 |
| 5. | &mdash; | Safari | 17.2.1<br>(19617.1.17.11.12) | &mdash; | 4133.80 ± 29.49% | 2023-12-19 |
| 6. | &mdash; | Orion | 0.99.126.4.1-beta<br>(WebKit 618.1.2) | &mdash; | 3736.60 ± 14.89% | 2023-12-19 |
| 7. | 5. | Brave | 1.61.104 | 120.0.6099.115 | 3507.12 ± 9.91% | 2023-12-19 |
| 8. | &mdash; | Mozilla Firefox | 121.0 | &mdash; | 1584.07 ± 6.68% | 2023-12-19 |

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Arithmetic Mean: 432 ± 16 (3.8%)
Iteration 1	378.8 runs/min
Iteration 2	421.6 runs/min
Iteration 3	437.2 runs/min
Iteration 4	423.2 runs/min
Iteration 5	424.6 runs/min
Iteration 6	443.0 runs/min
Iteration 7	446.6 runs/min
Iteration 8	432.7 runs/min
Iteration 9	458.4 runs/min
Iteration 10	456.0 runs/min

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-19
Arithmetic Mean: 425 ± 16 (3.7%)
Iteration 1	375.3 runs/min
Iteration 2	410.4 runs/min
Iteration 3	453.6 runs/min
Iteration 4	438.9 runs/min
Iteration 5	423.5 runs/min
Iteration 6	439.2 runs/min
Iteration 7	437.5 runs/min
Iteration 8	434.7 runs/min
Iteration 9	420.1 runs/min
Iteration 10	412.3 runs/min

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Arithmetic Mean: 416 ± 20 (4.8%)
Iteration 1	340.4 runs/min
Iteration 2	422.3 runs/min
Iteration 3	424.1 runs/min
Iteration 4	435.3 runs/min
Iteration 5	424.2 runs/min
Iteration 6	427.3 runs/min
Iteration 7	424.4 runs/min
Iteration 8	422.0 runs/min
Iteration 9	434.8 runs/min
Iteration 10	408.3 runs/min

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Arithmetic Mean: 478 ± 25 (5.2%)
Iteration 1	381.4 runs/min
Iteration 2	480.0 runs/min
Iteration 3	489.5 runs/min
Iteration 4	496.6 runs/min
Iteration 5	476.3 runs/min
Iteration 6	503.0 runs/min
Iteration 7	488.9 runs/min
Iteration 8	493.1 runs/min
Iteration 9	490.1 runs/min
Iteration 10	481.3 runs/min

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-19
Arithmetic Mean: 425 ± 22 (5.3%)
Iteration 1	343.5 runs/min
Iteration 2	417.8 runs/min
Iteration 3	438.8 runs/min
Iteration 4	442.3 runs/min
Iteration 5	417.1 runs/min
Iteration 6	444.9 runs/min
Iteration 7	453.9 runs/min
Iteration 8	439.6 runs/min
Iteration 9	434.1 runs/min
Iteration 10	417.0 runs/min

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Arithmetic Mean: 414 ± 17 (4.1%)
Iteration 1	370.3 runs/min
Iteration 2	420.2 runs/min
Iteration 3	432.5 runs/min
Iteration 4	439.2 runs/min
Iteration 5	410.3 runs/min
Iteration 6	432.9 runs/min
Iteration 7	427.0 runs/min
Iteration 8	419.9 runs/min
Iteration 9	374.3 runs/min
Iteration 10	414.3 runs/min

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Arithmetic Mean: 455 ± 24 (5.2%)
Iteration 1	360.9 runs/min
Iteration 2	467.0 runs/min
Iteration 3	462.1 runs/min
Iteration 4	464.0 runs/min
Iteration 5	463.2 runs/min
Iteration 6	466.5 runs/min
Iteration 7	470.0 runs/min
Iteration 8	468.7 runs/min
Iteration 9	470.5 runs/min
Iteration 10	452.8 runs/min

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-19
Arithmetic Mean: 424 ± 18 (4.3%)
Iteration 1	372.1 runs/min
Iteration 2	440.9 runs/min
Iteration 3	440.2 runs/min
Iteration 4	436.4 runs/min
Iteration 5	450.5 runs/min
Iteration 6	404.2 runs/min
Iteration 7	433.5 runs/min
Iteration 8	392.9 runs/min
Iteration 9	438.3 runs/min
Iteration 10	432.7 runs/min

#### JetStream raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Score: 341.568

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-19
Score: 324.771

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 236.463

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Score: 360.445

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-19
Score: 346.891

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Score: 348.946

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Score: 358.589

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-19
Score: 329.877

#### MotionMark raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Score: 4438.72 ± 14.42%

Brave v.1.61.104 Chromium: 120.0.6099.115 (Official Build) (arm64)
2023-12-19
Score: 3507.12 ± 9.91%

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 1584.07 ± 6.68%

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Score: 4133.80 ± 29.49%

Microsoft Edge v.120.0.2210.77 (Official build) (arm64)
Chromium v.120.0.6099.110
2023-12-19
Score: 4650.73 ± 17.15%

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Score: 4532.02 ± 19.92%

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Score: 3736.60 ± 14.89%

Vivaldi v.6.5.3206.39 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-19
Score: 4301.27 ± 14.11%

-->