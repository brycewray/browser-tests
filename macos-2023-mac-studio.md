# Web browser tests on macOS

*OS, system, and testing specs at bottom.*

----

## [Speedometer 2.1](https://browserbench.org/Speedometer2.1/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | 1. | Opera | 496 ± 24 (4.8%) | 2023-12-23 |
| 2. | &mdash; | Safari  | 478 ± 25 (5.2%) | 2023-12-19 |
| 3. | &mdash; | Orion | 455 ± 24 (5.2%) | 2023-12-19 |
| 4. | 2. | Vivaldi | 441 ± 24 (5.4%) | 2023-12-22 |
| 5. | 3. | Google Chrome | 432 ± 16 (3.8%) | 2023-12-20 |
| 6. | 4. | Microsoft Edge | 425 ± 21 (4.9%) | 2023-12-21 |
| 7. | 5. | Brave | 418 ± 21 (5.1%) | 2023-12-21 |
| 8. | &mdash; | Mozilla Firefox | 416 ± 20 (4.8%) | 2023-12-19 |
| 9. | 6. | Arc | 414 ± 17 (4.1%) | 2023-12-19 |

----

## [JetStream 2.1](https://browserbench.org/JetStream/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | &mdash; | Safari | 360.445 | 2023-12-19 |
| 2. | &mdash; | Orion | 358.589 | 2023-12-19 |
| 3. | 1. | Vivaldi | 354.404 | 2023-12-22 |
| 4. | 2. | Opera | 353.422 | 2023-12-23 |
| 5. | 3. | Brave | 349.077 | 2023-12-21 |
| 6. | 4. | Arc | 348.946 | 2023-12-19 |
| 7. | 5. | Google Chrome | 341.568 | 2023-12-20 |
| 8. | 6. | Microsoft Edge | 338.092 | 2023-12-21 |
| 9. | &mdash; | Mozilla Firefox | 236.463 | 2023-12-19 |

----

## [MotionMark 1.2](https://browserbench.org/MotionMark1.2/)

| Rank | Chromium<br>rank | [Browser](/browsers.md) | Score | Date |
|--:|--:|:-:|:-:|--:|
| 1. | 1. | Opera | 5183.02 ± 22.04% | 2023-12-23 |
| 2. | 2. | Microsoft Edge | 4636.72 ± 14.53% | 2023-12-21 |
| 3. | 3. | Arc | 4532.02 ± 19.92% | 2023-12-19 |
| 4. | 4. | Google Chrome | 4438.72 ± 14.42% | 2023-12-20 |
| 5. | 5. | Vivaldi | 4335.83 ± 19.75% | 2023-12-22 |
| 6. | &mdash; | Safari | 4133.80 ± 29.49% | 2023-12-19 |
| 7. | &mdash; | Orion | 3736.60 ± 14.89% | 2023-12-19 |
| 8. | 6. | Brave | 3605.20 ± 16.06% | 2023-12-21 |
| 9. | &mdash; | Mozilla Firefox | 1584.07 ± 6.68% | 2023-12-19 |

----

## OS, system, and testing specs

- macOS Sonoma v.14.2.1
- Mac Studio (mid-2023 version)
  - M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64GB RAM
  - Internal graphics running 5120 × 2880 at 2x (“Retina”)
- Each browser is [current stable desktop version](/browsers.md) on date of test, running in a private window with disabling of all extensions and tracking protection.
- On MotionMark test, all results “on a large screen (desktop)” as per instructions.

<!--
----

### *Raw data*

*(Unformatted for Markdown; best viewed in “raw” form on GH/GL.)*

#### Speedometer raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Arithmetic Mean: 432 ± 16 (3.8%)

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (arm64)
2023-12-21
Arithmetic Mean: 418 ± 21 (5.1%)

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Arithmetic Mean: 416 ± 20 (4.8%)

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Arithmetic Mean: 478 ± 25 (5.2%)

Microsoft Edge v.120.0.2210.91 (Official build) (arm64)
Chromium v.120.0.6099.130
2023-12-21
Arithmetic Mean: 425 ± 21 (4.9%)

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Arithmetic Mean: 414 ± 17 (4.1%)

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Arithmetic Mean: 455 ± 24 (5.2%)

Vivaldi v.6.5.3206.42 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-22
Arithmetic Mean: 441 ± 24 (5.4%)

Opera v.106.0.4998.19 (arm64)
Chromium v.120.0.6099.130
2023-12-23
Arithmetic Mean: 496 ± 24 (4.8%)


#### JetStream raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Score: 341.568

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (arm64)
2023-12-21
Score: 349.077

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 236.463

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Score: 360.445

Microsoft Edge v.120.0.2210.91 (Official build) (arm64)
Chromium v.120.0.6099.130
2023-12-21
Score: 338.092

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Score: 348.946

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Score: 358.589

Vivaldi v.6.5.3206.42 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-22
Score: 354.404

Opera v.106.0.4998.19 (arm64)
Chromium v.120.0.6099.130
2023-12-23
Score: 353.422


#### MotionMark raw data

Google Chrome v.120.0.6099.129 (Official Build) (arm64)
2023-12-20
Score: 4438.72 ± 14.42%

Brave v.1.61.109 Chromium: 120.0.6099.144 (Official Build) (arm64)
2023-12-21
Score: 3605.20 ± 16.06%

Mozilla Firefox v.121.0 (64-bit)
2023-12-19
Score: 1584.07 ± 6.68%

Safari v.17.2.1 (19617.1.17.11.12)
2023-12-19
Score: 4133.80 ± 29.49%

Microsoft Edge v.120.0.2210.91 (Official build) (arm64)
Chromium v.120.0.6099.130
2023-12-21
Score: 4636.72 ± 14.53%

Arc v.1.21.1 (44329)
Chromium v.120.0.6099.109 (Official Build) (arm64)
2023-12-19
Score: 4532.02 ± 19.92%

Orion v.0.99.126.4.1-beta (WebKit 618.1.2)
2023-12-19
Score: 3736.60 ± 14.89%

Vivaldi v.6.5.3206.42 (Stable channel) (arm64)
Chromium v.120.0.6099.121
2023-12-22
Score: 4335.83 ± 19.75%

Opera v.106.0.4998.19 (arm64)
Chromium v.120.0.6099.130
2023-12-23
Score: 5183.02 ± 22.04%

-->