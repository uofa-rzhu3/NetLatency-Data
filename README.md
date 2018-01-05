# Network Latency Datasets

This repository consists datasets of network latencies which we collected from two public network platforms: `PlanetLab` and `Seattle`. Please feel free to contact us if you have any comments or questions.

---

### Seattle Dataset

**688 time slices of RTTs between 99 nodes in the Seattle network**

This dataset consists of round trip times (RTTs) between 99 nodes in the Seattle network over 688 time slices.

The file name of each frame is as the format `SeattleData_t`, where `t` is the number of the time slice for this frame. The number `t` ranges from 1 to 688. Each file is a 99x99 matrix, where the (*i*, *j*)-th entry indicates the measured RTT from node *i* to node *j*.


### PlanetLab Dataset

**18 time slices of RTTs between 490 nodes in the PlanetLab network**

This dataset consists of round trip times (RTTs) between 490 nodes in the PlanetLab network over 18 time slices.

The file name of each frame is as the format `PlanetLabData_t`, where `t` is the number of the time slice for this frame. The number `t` ranges from 1 to 18. Each file is a 490x490 matrix, where the (*i*, *j*)-th entry indicates the measured RTT from node *i* to node *j*.


---

## Citation

IF YOU USE THIS PACKAGE IN ANY PUBLISHED RESEARCH, PLEASE KINDLY CITE THE FOLLOWING PAPER:

Rui Zhu, Bang Liu, Di Niu, Zongpeng Li, Hong Vicky Zhao, "Network Latency Estimation for Personal Devices: A Matrix Completion Approach", IEEE/ACM Transactions on Networking, vol. 25, no. , pp. 724-737, April 2017.

## Acknowledgements
- Seattle (https://seattle.poly.edu/) for use to collect the dataset
- PlanetLab (http://www.planet-lab.org/) for use to collect the dataset

## License
The MIT License (MIT)

