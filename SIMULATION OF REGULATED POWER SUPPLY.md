# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:

![WhatsApp Image 2025-11-28 at 16 59 23_6e546639](https://github.com/user-attachments/assets/9303f088-63a5-43a4-8916-3b6e9c9822df)

## AC INPUT WAVEFORM:

![WhatsApp Image 2025-11-28 at 16 52 50_728e7b4e](https://github.com/user-attachments/assets/9feae15d-ce68-4896-9a01-05919e729988)

## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)

![WhatsApp Image 2025-11-28 at 16 52 50_8b051b3a](https://github.com/user-attachments/assets/523e9e46-29f4-42af-92d7-55c9bc82ddbd)

## SIGNAL OUTPUT(WITH FILTER)

![WhatsApp Image 2025-11-28 at 16 52 49_3a2e9ef0](https://github.com/user-attachments/assets/62c6dac1-a3e8-4776-97d8-53c47e55fbb7)

## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
