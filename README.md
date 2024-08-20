# VLSI-Common-Source-Amplifier-DesignFlow
This project covers the complete design process for a common source amplifier, a key component in analog electronics. 

**1. Schematic Design**


The schematic design for the common source amplifier includes PMOS and NMOS transistors, with VDD connected to the drain of the PMOS transistor and VSS connected to the source of the NMOS transistor. The circuit also features VBIAS for transistor biasing, and input and output pins for signal connections. This schematic forms the basis for the amplifier’s operation and subsequent design stages.



![Screenshot from 2024-08-17 11-29-52](https://github.com/user-attachments/assets/b8c5d70d-84dc-414f-bffc-27b9d5d46932)


The schematic diagram shows how these components are connected to create a common source amplifier, which is a fundamental building block in circuit design.

**2. Symbol Creation:**

The symbol creation for the common source amplifier involves designing a graphical representation of the circuit for use in schematic diagrams. The symbol includes:

Pin Configuration: Clearly labeled pins for input, output, VDD, VSS, Vin, and VBIAS.
Visual Representation: A compact and recognizable symbol that reflects the common source amplifier’s functionality.


![Screenshot from 2024-08-17 11-44-12](https://github.com/user-attachments/assets/76217269-60ab-4bbd-b218-66060a536eaa)


This symbol facilitates the integration of the common source amplifier into larger circuit designs.


**3.Testbench Setup **
The testbench setup for the common source amplifier includes:
Pulse Source (VPULSE): Provides a time-varying signal to the amplifier's input for response testing.
DC Voltage Source (VDC): Supplies a steady DC voltage connected to both VDD and VBIAS to power the amplifier and set the biasing conditions.
Connections: The VPULSE source is connected to the amplifier's input pin. The VDC source is connected to VDD, VBIAS, and VSS to ensure proper operation and biasing of the circuit. The output pin of the amplifier is monitored to evaluate the amplifier’s performance.



![Screenshot from 2024-08-17 11-50-28](https://github.com/user-attachments/assets/fcfddccb-a819-4fcb-9ffe-9cf8cc5e2997)


This configuration allows for comprehensive simulation and testing of the amplifier’s functionality.
