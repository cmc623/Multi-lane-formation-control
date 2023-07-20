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

[1] Cai M, Xu Q, Chen C, et al. Multi-lane unsignalized intersection cooperation with flexible lane direction based on multi-vehicle formation control[J]. IEEE Transactions on Vehicular Technology, 2022, 71(6): 5787-5798. (https://ieeexplore.ieee.org/abstract/document/9740423/)

[2] Xu Q, Cai M, Li K, et al. Coordinated formation control for intelligent and connected vehicles in multiple traffic scenarios[J]. IET Intelligent Transport Systems, 2021, 15(1): 159-173. (https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/itr2.12022)

[3] Cai M, Xu Q, Li K, et al. Multi-lane formation assignment and control for connected vehicles[C]//2019 IEEE Intelligent Vehicles Symposium (IV). IEEE, 2019: 1968-1973. (https://ieeexplore.ieee.org/abstract/document/8813792)

[4] Cai M, Xu Q, Chen C, et al. Formation control with lane preference for connected and automated vehicles in multi-lane scenarios[J]. Transportation research part C: emerging technologies, 2022, 136: 103513. (https://www.sciencedirect.com/science/article/pii/S0968090X21004964)

[5] Cai M, Xu Q, Chen C, et al. Formation control for connected and automated vehicles on multi‐lane roads: Relative motion planning and conflict resolution[J]. IET Intelligent Transport Systems, 2023, 17(1): 211-226. (https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/itr2.12249)

[6] Cai M, Xu Q, Chen C, et al. Formation control for multiple connected and automated vehicles on multi-lane roads[C]//2021 IEEE International Intelligent Transportation Systems Conference (ITSC). IEEE, 2021: 1940-1945. (https://ieeexplore.ieee.org/abstract/document/9564760)


Corresponding E-mail: 

caimengchi@mail.tsinghua.edu.cn

qingxu@tsinghua.edu.cn

likq@tsinghua.edu.cn

Follow my updates on Researchgate: https://www.researchgate.net/profile/Mengchi-Cai
