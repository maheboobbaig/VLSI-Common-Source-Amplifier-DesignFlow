# VLSI-Common-Source-Amplifier-DesignFlow
This project covers the complete design process for a common source amplifier, a key component in analog electronics. 

**1. Schematic Design:**
The schematic design for the common source amplifier includes PMOS and NMOS transistors, with VDD connected to the drain of the PMOS transistor and VSS connected to the source of the NMOS transistor. The circuit also features VBIAS for transistor biasing, and input and output pins for signal connections. This schematic forms the basis for the amplifier’s operation and subsequent design stages.



![Screenshot from 2024-08-17 11-29-52](https://github.com/user-attachments/assets/b8c5d70d-84dc-414f-bffc-27b9d5d46932)


The schematic diagram shows how these components are connected to create a common source amplifier, which is a fundamental building block in circuit design.

**2. Symbol Creation:**
The symbol creation for the common source amplifier involves designing a graphical representation of the circuit for use in schematic diagrams. The symbol includes:

Pin Configuration: Clearly labeled pins for input, output, VDD, VSS, and VBIAS.
Visual Representation: A compact and recognizable symbol that reflects the common source amplifier’s functionality.


![Screenshot from 2024-08-17 11-51-14](https://github.com/user-attachments/assets/5daf0b5a-56d1-4fc7-af12-fb62fd5fa268)




This symbol facilitates the integration of the common source amplifier into larger circuit designs.


**3.Testbench Setup:**
The testbench setup for the common source amplifier includes:
Pulse Source (VPULSE): Provides a time-varying signal to the amplifier's input for response testing.
DC Voltage Source (VDC): Supplies a steady DC voltage connected to both VDD and VBIAS to power the amplifier and set the biasing conditions.
Connections: The VPULSE source is connected to the amplifier's input pin. The VDC source is connected to VDD, VBIAS, and VSS to ensure proper operation and biasing of the circuit. The output pin of the amplifier is monitored to evaluate the amplifier’s performance.



![Screenshot from 2024-08-17 11-50-28](https://github.com/user-attachments/assets/fcfddccb-a819-4fcb-9ffe-9cf8cc5e2997)


This configuration allows for comprehensive simulation and testing of the amplifier’s functionality.

**4. Transient, DC and AC Analysis:**

**Transient Response:**
The transient analysis examines the behavior of the common source amplifier in response to time-varying input signals. This analysis provides insights into how the amplifier reacts dynamically.

Transient Response Results:

![Screenshot from 2024-08-17 12-23-46](https://github.com/user-attachments/assets/5ece9ba5-2ed4-43c6-b83f-84e6f5a3fa83)


The results show that when the input signal is high, the output signal is low, and when the input is low, the output is high. This behavior demonstrates that the common source amplifier functions as an inverting amplifier, where the output is the logical inversion of the input signal.

**DC Response:**
The DC analysis evaluates the common source amplifier’s performance with a steady DC input, focusing on its static operating point.

DC Response Results:


![Screenshot from 2024-08-17 12-45-42](https://github.com/user-attachments/assets/4f531111-3114-4e46-b85f-163e0c789a3b)


The graph illustrates the DC operating characteristics of the amplifier. It shows how the output voltage varies with changes in the input DC voltage, providing insights into the amplifier's biasing and static behavior.

**AC Response:**
The AC analysis investigates the frequency response of the common source amplifier, revealing how the amplifier performs with varying AC input signals.

AC Response Results:


![Screenshot from 2024-08-17 12-45-29](https://github.com/user-attachments/assets/3b6b70c7-4483-4291-95ae-a94fabc43163)

The plot shows the amplifier's response across different frequencies. It provides insight into how the amplifier's output varies with frequency, helping to assess its performance characteristics.

**Final Result**


![Screenshot from 2024-08-17 12-44-41](https://github.com/user-attachments/assets/2078b44d-a0dc-4e8c-b36c-d68d45705b37)



The final plot combines the results of transient, DC, and AC analyses. It provides a comprehensive view of the amplifier's performance across different analyses:
- **Transient Response**: Shows how the amplifier responds to time-varying inputs.
- **DC Response**: Displays the amplifier’s behavior conditions.
- **AC Response**: Illustrates how the amplifier performs with varying frequencies.

This integrated view helps to evaluate the overall performance and behavior of the common source amplifier across various operating conditions.

