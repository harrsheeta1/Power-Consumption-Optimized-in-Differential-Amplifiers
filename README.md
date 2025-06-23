# Power-Consumption-in-Differential-Amplifiers
This is the Project I made in the Minor Project-2. The project includes the design, simulation, and analysis of differential amplifier circuits using different load types.

## What is Differential Amplifier 
A differential amplifier amplifies the voltage difference between two inputs while rejecting any voltage common to both. It is widely used in analog circuits, operational amplifiers, and sensor applications. Its effectiveness is often evaluated by the Common-Mode Rejection Ratio (CMRR), which determines how well it rejects noise and interference.

## Simulation and Tools Used
Simulations were performed using Cadence Virtuoso with the 180nm CMOS technology node and a 1.8V supply. We conducted DC, AC, and transient analyses to study operating points, frequency response, gain, and time-domain behavior. Key features used:

- Schematic design of differential amplifier circuits
- Spectre simulations for detailed electrical analysis
  
## Topologies Analyzed

1. **Current Source Load**  
   - Better gain stability and improved current sourcing, with moderate power efficiency

2. **Active Load**  
   - Uses MOSFET-based loads to achieve high gain and lower power consumption

3. **Diode-Connected Load**  
   - Delivers the highest gain but at the cost of reduced bandwidth
     
## Results
Simulation results showed that diode connected and current source load configurations offered the best trade-off between gain and power consumption. Voltage Transfer Characteristic graphs and circuit diagrams were used to validate performance across different configurations.

## Applications
Differential amplifiers designed in this project are suitable for:

- Communication systems where signal integrity and low noise are critical
- Medical electronics such as ECG and EEG systems
## Future Work
This project successfully demonstrates methods for reducing power consumption in differential amplifier circuits. Future work may include designing full operational amplifiers using the optimized topologies and exploring smaller technology nodes for further efficiency.

## Screenshots
**Active Load**
![image](https://github.com/user-attachments/assets/30cce568-a4b4-40d3-b576-85935cae7151)
![image](https://github.com/user-attachments/assets/11724856-9795-4485-a7a5-b447ebb4b2eb)
![image](https://github.com/user-attachments/assets/c0ba58ad-500c-424a-9fda-0a3b3428d768)

**Current Source Load**
![image](https://github.com/user-attachments/assets/fd3589f8-5b7a-4ebf-b719-9fcb1d6436ed)
![image](https://github.com/user-attachments/assets/6e4791dd-4627-4421-b995-602cf376f067)
![image](https://github.com/user-attachments/assets/9cc48413-30d9-45da-901f-cbb8caa254ed)

**Diode Connected Load**
![image](https://github.com/user-attachments/assets/3ca55525-22d7-49be-a134-6b332388c1a4)
![image](https://github.com/user-attachments/assets/2002ef80-c971-48f6-8579-68b926ace6e0)

## Final Parameter Comparision Table
![image](https://github.com/user-attachments/assets/3007a7c6-f90d-4d63-b10b-167367666cd9)













