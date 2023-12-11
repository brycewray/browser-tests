# Web browser tests on macOS

## OS, system, and testing specs

- macOS Sonoma v.14.1.2
- Mac Studio (mid-2023 version)
- M2 Max (12-core CPU, 38-core GPU, 16-core Neural Engine), 64 GB RAM
- Each browser running in private window; disabled extensions and tracking protection

----

## Jetstream 2.1

URL: https://browserbench.org/JetStream/

| Rank | Chromium rank | Browser | Version | Chromium version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Orion | 0.99.126.3-beta (WebKit 618.1.2) | - | 366.347 | 2023-12-09 |
| 2. | 1. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 357.824 | 2023-12-09 |
| 3. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 357.274 | 2023-12-08 |
| 4. | 3. | Brave | 1.61.101 | 120.0.6099.71 | 355.752 | 2023-12-08 |
| 5. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 350.381 | 2023-12-08 |
| 6. | 4. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 338.623 | 2023-12-08 |
| 7. | - | Mozilla Firefox | 120.0.1 | - | 239.182 | 2023-12-08 |

----

## MotionMark 1.2

URL: https://browserbench.org/MotionMark1.2/

All results “on a large screen (desktop)” as per instructions

| Rank | Chromium rank | Browser | Version | Chromium version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | 1. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 4864.02 ± 11.71% | 2023-12-08 |
| 2. | 2. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 4583.58 ± 22.42% | 2023-12-08 |
| 3. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 4497.63 ± 14.03% | 2023-12-09 |
| 4. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 4461.82 ± 15.68% | 2023-12-08 |
| 5. | - | Orion | 0.99.126.3-beta (WebKit 618.1.2) | - | 3753.71 ± 19.97% | 2023-12-09 |
| 6. | 4. | Brave | 1.61.101 | 120.0.6099.71 | 3632.97 ± 27.96% | 2023-12-08 |
| 7. | - | Mozilla Firefox | 120.0.1 | - | 1800.21 ± 2.34% | 2023-12-08 |

----

## Speedometer 2.1

URL: https://browserbench.org/Speedometer2.1/

### By arithmetic mean

| Rank | Chromium rank | Browser | Version | Chromium version | Score | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Orion | 0.99.126.3-beta (WebKit 618.1.2) | - | 458 ± 27 (5.9%) | 2023-12-09 |
| 2. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 457 ± 21 (4.6%) | 2023-12-08 |
| 3. | - | Mozilla Firefox | 120.0.1 | - | 439 ± 27 (6.2%) | 2023-12-08 |
| 4. | 1. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 413 ± 21 (5.2%) | 2023-12-08 |
| 5. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 410 ± 22 (5.3%) | 2023-12-08 |
| 6. | 3. | Brave | 1.61.101 | 120.0.6099.71 | 404 ± 23 (5.7%) | 2023-12-08 |
| 7. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 399 ± 21 (5.2%) | 2023-12-09 |

### By BEST RESULT of 10 iterations

| Rank | Chromium rank | Browser | Version | Chromium version | Runs/min. | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Orion | 0.99.126.3-beta (WebKit 618.1.2) | - | 494.4 | 2023-12-09 |
| 2. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 475.1 | 2023-12-08 |
| 3. | - | Mozilla Firefox | 120.0.1 | - | 469.7 | 2023-12-08 |
| 4. | 1. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 441.7 | 2023-12-08 |
| 5. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 433.7 | 2023-12-08 |
| 6. | 3. | Brave | 1.61.101 | 120.0.6099.71 | 425.6 | 2023-12-08 |
| 7. | 4. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 421.8 | 2023-12-09 |

### By WORST RESULT of 10 iterations

| Rank | Chromium rank | Browser | Version | Chromium version | Runs/min. | Date |
|:--|:--|:--|:-:|:-:|:-:|:-:|
| 1. | - | Safari | 17.1.2 (19616.2.9.11.12) | - | 380.1 | 2023-12-08 |
| 2. | - | Orion | 0.99.126.3-beta (WebKit 618.1.2) | - | 360.4 | 2023-12-09 |
| 3. | 1. | Microsoft Edge | 120.0.2210.61 | 120.0.6099.71 | 336.3 | 2023-12-08 |
| 4. | - | Mozilla Firefox | 120.0.1 | - | 336.2 | 2023-12-08 |
| 5. | 2. | Google Chrome | 120.0.6099.71 | 120.0.6099.71 | 330.9 | 2023-12-08 |
| 6. | 3. | Arc | 1.20.1 (43987) | 120.0.6099.56 | 321.2 | 2023-12-09 |
| 7. | 4. | Brave | 1.61.101 | 120.0.6099.71 | 315.3 | 2023-12-08 |
