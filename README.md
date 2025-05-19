# LED-Propeller-Clock

This project showcases a Persistence of Vision (POV) display utilizing LED lights and an Arduino Nano microcontroller. When the LED assembly is rotated at a specific speed, it creates visually coherent patterns or text based on the programmed code in the Arduino. The system is powered by a 9V lead-acid battery, which is regulated through a 7805 voltage regulator IC to ensure a stable 5V supply to the components. This setup allows for reliable and consistent current flow. All ground (negative) connections are properly referenced and routed through 150-ohm resistors to ensure appropriate current limiting for the LEDs.

The spinning motion of the LED array is driven by a DC motor, and the speed is regulated to maintain the correct projection and display output. The combination of mechanical motion and precise control via the Arduino enables the successful demonstration of the POV effect.

# Materials Required

1. LED-(8)
2. Arduino Nano
3. Lead Acid Battery - 9V
4. Push Switch 
5. IC 7805
6. 150 OHM Resistor
7. Battery Connector
8. Wires And Tags
9. Zero PCB Board
10. Angle griender connector set

# Procedure 

Step 1: Cut a section of the zero PCB board to the required size for the project.

Step 2: Place the 8 LEDs on the board, solder all the negative terminals in parallel, and connect a 150-ohm resistor to the common ground leg.

Step 3: Extend and solder wires to each of the positive legs of the LEDs for individual connections.

Step 4: Connect the wires from the positive legs of the LEDs to the Arduino Nano’s digital pins D2 to D9, in sequence starting from the end nearest to the resistor.

Step 5: Connect a wire from the GND pin of the Arduino Nano to the negative end of the 150-ohm resistor to complete the common ground connection.

Step 6: Use a 9V lead-acid battery and connect it to the IC 7805 voltage regulator as follows: mount the IC with its three legs separated—connect the left leg (input) to the positive terminal of the battery, the center leg (ground) to both the Arduino Nano’s GND pin and the battery’s negative terminal, and the right leg (output) to one terminal of the push switch.

Step 7: Solder a wire from the other terminal of the push switch and connect it to the 5V pin of the Arduino Nano to supply regulated power.

Step 8: Use a 15 cm wooden or PVC sheet as the base to mount all the components in an organized manner. Accurately locate the center of the sheet and securely attach an angle grinder connector at this point. Ensure the components are evenly distributed around the center to maintain proper balance during rotation and minimize vibration.

