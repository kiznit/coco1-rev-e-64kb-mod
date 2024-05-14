# coco1-rev-e-64kb-mod
This project contains two breakout boards to upgrade a CoCo 1 Rev E from 32KB to 64KB without having to solder directly to U11 and U29.

- The first adapter for U29 (74LS02) has two PIN headers: one needs to be connected to **TP1** next to the CPU and the other to **U29** on U11's adapter.
- The second adapter for U11 (73LS138) has one PIN header that needs to be connected to **U11** on U29's adapter.

The **bin** folder contains zip files that can be uploaded directly to JLBPCB for production.

Update 2024/05/13:
I have assembled and tested the PCBs in my Rev E CoCo 1 and they work! I can now run 64 KB games like Sailor Man.

![CoCo 1 Rev E with PCB boards - no wires](./photo1.jpg)
![CoCo 1 Rev E with PCB boards - with wires](./photo2.jpg)
![CoCo 1 Rev E with PCB boards - overview](./photo3.jpg)
