---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Tushar Muley
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     | 

TM- Using ASCII character set each character is 1 byte so 128 bytes

*************
| 1024x768 PNG image                         | 0.45704 MB    | 

TM- Use an online calculator and doubled using a different one.
    Site 1 - 457.04KB or 0.45704MB for a 24bit image with 16.7million colors
    Site 2 - 4608kb or 4.608MB for a 48bit

Reference:
Oncline calculator
https://toolstud.io/photo/megapixel.php?width=1024&height=768&compare=video&calculate=compressed#calculate 
https://jan.ucc.nau.edu/lrm22/pixels2bytes/calculator.htm
*************
| 1024x768 RAW image                         | 0.68813 MB    | 

TM - Using a online calculator a 1024x768 RAW image on a Canon sRAW CR2 would be 0.68813MB or 688.13KB compressed
     Canon mRAW CR2	1.03MB   
     If you use uncompressed RAW/DNG 16 bits/pixel	1.57MB


*************
| HD (1080p) HEVC Video (15 minutes)         | 641.25MB          |

TM - Total video file size 900 seconds x 5.7MB/sec
5.13GB or 641.25 (5.13*125)

Reference:
Using a online calculator
https://toolstud.io/video/filesize.php?width=1920&height=1080&framerate=30&timeduration=15&timeduration_unit=minutes&compression=91628&specificbitrate=100&specificbitrate_unit=1000000

*************
| HD (1080p) Uncompressed Video (15 minutes) | 160,180.66MB          |

TM - Using calculaiton on stackoverflow.com

Part1:
Size of resultion (1920x1080 resolution of 1080P) x 3 bytes per pixel x 30 frames per second / (1024x1024 bytes per megabyte) than

Part2:
Take the total from part 1 which is in MB/s * 60sec*15minutes (lenght of video) = 

1920 x 1080 x 3 x 30frames per second / (1024x1024 bytes per megabytes) =  177.98 MB/s
177.98 MB/s * 60 sec*15min =  160,180.66 MB or  156.43GB

Reference:
https://stackoverflow.com/questions/27559103/video-size-calculation

*************
| 4K UHD HEVC Video (15 minutes)             | 2,565 MB          |

TM - Using the UHD screen size of 3840x2160 and HEVC and 24bit RGB you get a compressed size of 20.52GB or 2,565 MB. 

Reference:
Online calculator
https://toolstud.io/video/filesize.php?width=3840&height=2160&framerate=30&timeduration=15&timeduration_unit=minutes&compression=91628&specificbitrate=100&specificbitrate_unit=1000000

*************
| 4k UHD Uncompressed Video (15 minutes)     | 640,722.6 MB          |

TM - This got a little complex. Using the below calculation from Slackoverflow.

Part1:
Size of resultion (3840x2160 UHD Video size) x 3 bytes per pixel x 30 frames per second / (1024x1024 bytes per megabyte) than

Part2:
Take the total from part 1 which is in MB/s * 60sec*15minutes (lenght of video) = 

3840 x 2160 x 3 x 30frames per second / (1024x1024 bytes per megabytes) = 711.914 MB/s
711.914 MB/s * 60 sec*15min =  640,722.6 MB or 625.71 GB

Reference:
https://stackoverflow.com/questions/27559103/video-size-calculation

*************
| Human Genome (Uncompressed)                | 0.7 GB          |

TM - I found this online at medium.com
https://medium.com/precision-medicine/how-big-is-the-human-genome-e90caa3409b0

Reference:
Robinson, R MD MBA. (June 2014). "How big is the human genome?". From Medium.com. 
https://medium.com/precision-medicine/how-big-is-the-human-genome-e90caa3409b0

#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | ??       |      |
| Daily Twitter Tweets (Snappy Compressed)  | ??       |      |
| Daily Instagram Photos                    | ??       |      |
| Daily YouTube Videos                      | ??       |      |
| Yearly Twitter Tweets (Uncompressed)      | ??       |      |
| Yearly Twitter Tweets (Snappy Compressed) | ??       |      |
| Yearly Instagram Photos                   | ??       |      |
| Yearly YouTube Videos                     | ??       |      |

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | ??   |            |
| Twitter Tweets (Snappy Compressed) | ??   |            |
| Instagram Photos                   | ??   |            |
| YouTube Videos                     | ??   |            |

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | ? ms                 |
| Low Earth Orbit Satellite | ? ms                 |
| Geostationary Satellite   | ? ms                 |
| Earth to the Moon         | ? ms                 |
| Earth to Mars             | ? minutes            | 
