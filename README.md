# Multi-lane-formation-control

Coordinated decision making and control can improve traffic efficiency while guaranteeing driving safety. This paper proposes a formation control method for multiple Connected and Automated Vehicles (CAVs) on multi-lane roads. Firstly, a bi-level planning framework is proposed to switch the structure of the formation in different scenarios smoothly and effectively. Secondly, the relative coordinate system is established and the conflict-free relative paths are planned in the upper level. Then, multi-stage trajectory planning and tracking are modeled and solved as an optimal control problem with constraints in the lower level. Next, case study is conducted to verify the function of the proposed method in different scenarios. Finally, simulation in the lane-drop bottleneck scenario is carried out under different traffic volume and numerical results indicate that the proposed method can improve both traffic efficiency and fuel economy at high traffic volume.

## The video (full version) can be seen in the attachments, and here we provide some segmental GIFs.

### Case study
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/GIF%20case%20study.gif" width="700" />

### Simulation of formation control
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/frc%2000_00_00-00_00_30.gif" width="700" />

### Simulation of SUMO default model
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/ref%2000_00_00-00_00_30.gif" width="700" />

### Simulation of pre-lane-changing method
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/ref2%2000_00_00-00_00_30.gif" width="700" />

### Simulation of single-lane platooning control (1 vehicle in each platoon)
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/ref3-1%2000_00_00-00_00_30.gif" width="700" />

### Simulation of single-lane platooning control (3 vehicles in each platoon)
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/ref3-3%2000_00_00-00_00_30.gif" width="700" />

### Simulation of single-lane platooning control (6 vehicles in each platoon)
<img src="https://github.com/cmc623/Multi-lane-formation-control/blob/main/ref3-6%2000_00_00-00_00_30.gif" width="700" />

For further details, please refer to:

[1] Cai M, Xu Q, Chen C, et al. Formation Control for Multiple Connected and Automated Vehicles on Multi-lane Roads[C]. Accepted by IEEE International Conference on Intelligent Transportation Systems, 2021. (https://arxiv.org/abs/2103.10287)

[2] Cai M, Xu Q, Chen C, et al. Formation Control for Connected and Automated Vehicles on Multi-lane Roads: Relative Motion Planning and Conflict Resolution[J]. arXiv preprint arXiv:2103.10287v3, 2021. (https://arxiv.org/abs/2103.10287)

[3] Cai M, Chen C, Wang J, et al. Formation Control with Lane Preference for Connected and Automated Vehicles in Multi-lane Scenarios[J]. arXiv preprint arXiv:2106.11763, 2021. (https://arxiv.org/abs/2106.11763)

[4] Cai M, Xu Q, Chen C, et al. Multi-lane Unsignalized Intersection Cooperation with Flexible Lane Direction based on Multi-vehicle Formation Control[J]. arXiv preprint arXiv:2108.11112, 2021. (https://arxiv.org/abs/2108.11112)


Corresponding E-mail: 

cmc18@mails.tsinghua.edu.cn

qingxu@tsinghua.edu.cn

likq@tsinghua.edu.cn

Follow my updates on Researchgate: https://www.researchgate.net/profile/Mengchi-Cai

This work was supported by the National Key Research and Development Program of China under Grant 2018YFE0204302, the National Natural Science Foundation of China under Grant 52072212, and Intel Collaborative Research Institute Intelligent and Automated Connected Vehicles. 
