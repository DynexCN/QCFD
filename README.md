# QCFD
在计算流体力学（CFD）中实施量子计算（QC）的 QUBO/Ising 问题，使用基于 ，由 Sachin S. Bharadwaj 和 Katepalli R. Sreenivasan，机械与航空工程系，STO - 教育笔记纸，2022 年编写。[An Introduction to Algorithms in Quantum Computation of Fluid Dynamics 的 DYNEX 神经形态计算](https://www.sto.nato.int/publications/STO%20Educational%20Notes/STO-EN-AVT-377/EN-AVT-377-01.pdf), 由 Sachin S. Bharadwaj 和 Katepalli R. Sreenivasan，机械与航空工程系，STO - 教育笔记论文，2022 年编写。

- [文件](https://github.com/dynexcoin/QCFD/blob/main/QCFD_Documentation.pdf)
- [视频](https://github.com/dynexcoin/QCFD/raw/main/IMG_7574.MP4)
- [案例](https://github.com/dynexcoin/QCFD/blob/main/QCFD_Examples.ipynb)

![图片](https://github.com/DynexCN/blob/main/imgs/4.png)

该存储库提供了一个Python类，用于将通常用于在量子计算机上解决线性系统的Harrow-Hassidim-Lloyd（HHL）算法转换为在DYNEX神经形态网络上计算的二次无约束二值优化（QUBO）模型，称为”QCFD”。该适应允许使用经典和量子启发求解器（即模拟退火采样器）和DYNEX网络用户寻找解决方案。

诸如湍流流动、玻璃系统、蛋白质折叠和化学反应等多个物理系统，在甚至最大的超级计算机上进行“有效”模拟都非常困难。然而，随着高性能计算（HPC）技术和同样“高效”的算法的发展，特别是计算流体动力学（CFD），在过去几十年里取得了巨大进展。由Navier-Stokes方程支配的湍流流动的一些最先进的直接数值模拟（DNS）在极大的雷诺数（Re）和高分辨率下模拟流动。这些模拟不仅揭示了流体物理的微观细节，而且测试了它们运行的超级计算机的极限。例如，让我们参考图1，它显示了HPC，各向同性DNS模拟随着时间和计算能力的增长是如何演变的，从323到≈ 180003网格点模拟（a-f）。我们看到它大致与摩尔定律保持一致。[Dynex神经形态计算平台](https://live.dynexcoin.org/cn)提供了一个平台，以克服这些限制。




