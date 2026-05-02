# Lithium Battery Charger and Boost Converter PCB

This PCB is designed to charge a 1S configuration LiPo Battery at 300mA and provide a stable 5V output.
Power Path Management is integrated using PMOS.
Only overcharge protection is supported.

# Features
- **CHarging IC**: TP4056 with 300mA of charge current.
- **Boost Converter**: MT3608 set to output 5V.
- **Power Path Mangement**: The PCB can simultaneouly charge the battery and provide output from input power provided. Integrated using a P Channel MOSFET.

# Images

**3D Renderings**
- Front View:

![Front Copper Layer](/images/3D_Front.png)

- Back View:

![Back Copper Layer](/images/3D_Back.png)

**PCB**

**2 Layer Board** - GND pour on both planes.

- Front Layer:

![Front Copper Layer](/images/F_Cu.png)

- Back Layer:

![Front Copper Layer](/images/B_Cu.png)

