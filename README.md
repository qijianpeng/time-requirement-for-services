# Time Requirement for Services (Application/Software end-to-end latency)
I've found it a challenging game for recording the numerous services with
their time constraint. However, recording these things may be very useful for
the design of the algorithms and systems. So, if you are interested in this
repo, we can together improve it.

These delay bounds can be used in, but not limited to:
- TSN (Time-Sensitive Network), which requires end-to-end latency no more
  than a given threshold.



| Application/Scenario |  Delays |  Bandwidth | Src  |
|           ---        |    ---  |      ---   | ---  | 
| Extreme VR           |  10 ms  |    1 Gbps (smooth play) / 2.35 Gbps (interactive) |  [DOI: 10.1145/3097895.3097901](https://dl.acm.org/doi/10.1145/3097895.3097901)
| Remote surgery  (远程手术, in Chinese)     | 1~10 ms |    300Mbps |  [ppt, page 2](http://www.ecconsortium.net/Uploads/file/20200506/20200506131731_63298.pdf)
| Robot collaboration (机器人协作, in Chinese) |   1 ms  |   1~10Mbps |  [ppt, page 2](http://www.ecconsortium.net/Uploads/file/20200506/20200506131731_63298.pdf)
| Smart venue (智慧场馆, in Chinese)          |  10 ms  |    1Gbps   |  [ppt, page 2](http://www.ecconsortium.net/Uploads/file/20200506/20200506131731_63298.pdf)
| XR (AR + VR )        |  5~20 ms  |    1Gbps   |  [DOI: 10.1145/3487552.3487815](https://doi.org/10.1145/3487552.3487815)


## Vehicle related
| Application/Scenario |  Delays |  Bandwidth | Src  |
|           ---        |    ---  |      ---   | ---  | 
| Accident prevention Time Sensitive-IoT application (intersection)        |  < 2~3s  |    -   |  [DOI: 10.1145/3510411](https://doi.org/10.1145/3510411)
| Autonomous           |   10 ms  |    50Mbps+ |  [DOI: 10.1145/3487552.3487815](https://doi.org/10.1145/3487552.3487815)
| Fuel theft prevention TS-IoT application        |  5~10s  |    -   |  [DOI: 10.1145/3510411](https://doi.org/10.1145/3510411)

## Latencies that infrastructure introduced 
| Infrastructure       |  RTT |     Range  | Data rate  |
|           ---        |    ---  |      ---   | ---        | 
|    Cellular (5G)     |    ~1 ms  |      ~100 km   |   ~20 Gbps     | 
|    UAVs/HAPS         |    ~3 ms  |      5-200 km   |    ~10 Gbps     | 
|    LEOs              |    30-50 ms  |     100-500 km   |    ~3.75 Gbps     | 
|    MEOs              |    135-250 ms  |      100-500 km   |    ~1.2 Gbps     | 
|    GEOs              |    560-800 ms |     200- 1,000 km  |    ~150 Mbps     | 
Refs: https://doi.org/10.1145/3606018

## Industrial Systems End-to-End Latency
| Service | End-to-End Latency | Src |
| --- | --- | --- |
| Factory automation (motion control) | 1 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Factory automation  | 10 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Process automation (remote control) | 50 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Process automation (monitoring) | 50 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Electricity distribution (medium voltage) | 25 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Electricity distribution (high voltage) | 5 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Intelligent transport systems (infrastructure backhaul) | 10 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |
| Remote Control | 5 ms | [DOI: 10.1145/3617591](https://doi.org/10.1145/3617591) |

# Other refs
- [Latency Numbers Every Programmer Should Know](https://colin-scott.github.io/personal_website/research/interactive_latency.html)

Contact: jianpengqi@126.com
