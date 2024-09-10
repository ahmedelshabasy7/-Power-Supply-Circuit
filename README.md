# -Power-Supply-Circuit
A Power Supply Circuit design using Altium Designer 

This is a voltage regulator circuit that uses a 7805 voltage regulator to provide a steady 5V output.

Here's a breakdown of the components and their roles:

J1 (PJ-002AH): This is a DC power jack connector. It allows for the input of a DC voltage from an external power source (e.g., a power adapter).

The pins are as follows:

Pin 1: GND (Ground)

Pin 2: Input voltage

Pin 3: Not connected (NC) or sometimes used as a switch depending on the jack design.  

U1 (7805CD2T): This is a 7805 voltage regulator, which regulates the input voltage (ranging from around 7V to 35V) and provides a stable 5V output. The pinout is:

Pin 1: IN (Input voltage)

Pin 2: GND (Ground)

Pin 3: OUT (5V output)

C1 (0.33 µF): This capacitor is used on the input side of the voltage regulator to filter out noise and stabilize the input voltage. It helps prevent oscillations in the regulator.

C2 (0.1 µF): This capacitor is placed on the output side to smooth the 5V output voltage and filter high-frequency noise, ensuring a stable output.

Circuit Explanation:

The circuit takes an unregulated DC input voltage (typically higher than 5V) via the J1 connector.
The 7805 voltage regulator (U1) steps down the input voltage to a regulated 5V.
The capacitors (C1 and C2) help filter the input and output to ensure a stable voltage free of noise or spikes.
The output is a steady 5V DC, which can be used to power devices requiring this specific voltage level.

In summary, this circuit is a simple power supply designed to deliver 5V DC with the help of a 7805 voltage regulator and capacitors to stabilize the input and output.
