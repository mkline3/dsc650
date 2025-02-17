---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Matt Kline
output: pdf_document
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |
| 1024x768 PNG image                         | 0.75 MB       |
| 1024x768 RAW image                         | 2.25 MB       | 
| HD (1080p) HEVC Video (15 minutes)         | 85995.52 MB   |
| HD (1080p) Uncompressed Video (15 minutes) | 171991.04 MB  |
| 4K UHD HEVC Video (15 minutes)             | 343961.6 MB   |
| 4k UHD Uncompressed Video (15 minutes)     | 687923.2 MB   |
| Human Genome (Uncompressed)                | 0.7 GB        |

#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | 12TB     |  1.2 |
| Daily Twitter Tweets (Snappy Compressed)  | 6TB      |  0.6 |
| Daily Instagram Photos                    | 10TB     |  1   |
| Daily YouTube Videos                      | 1PB      |  100 |
| Yearly Twitter Tweets (Uncompressed)      | 4.38PB   |  438 |
| Yearly Twitter Tweets (Snappy Compressed) | 2.19PB   |  219 |
| Yearly Instagram Photos                   | 3.65PB   |  365 |
| Yearly YouTube Videos                     | 365PB    | 36500|

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | 438  | 4.07       |
| Twitter Tweets (Snappy Compressed) | 219  | 2.03       |
| Instagram Photos                   | 365  | 3.39       |
| YouTube Videos                     | 36500| 340        |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 140.340 ms           |
| Low Earth Orbit Satellite | 270 ms               |
| Geostationary Satellite   | 270 ms               |
| Earth to the Moon         | 1300 ms              |
| Earth to Mars             | about 20 minutes     | 
