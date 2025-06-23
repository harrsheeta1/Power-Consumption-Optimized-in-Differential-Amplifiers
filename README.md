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




