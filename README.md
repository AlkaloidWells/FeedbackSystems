# FeedbackSystems
Three face grid  with PLL and a Simulation of An Automtic Gate using TIA Portal

                                    #INTRODUCTION
The Phase Locked Loop is a system that generates an output signal whose phase is related to the input. Here, the two signals will have the same frequency and with a phase difference between them. It is a closed loop with a control mechanism to reduce any phase error that may occur.
The Lab practice consisted of demonstrating the practical application of a PLL Circuit with physical electronics components. The block of operation for the PLL Circuit was mounted on an IC with a voltage regulator for supplying the input signal and an Oscilloscope for display.
The exercise involved three phases: The mounting of the PLL Block , the supply of the input signal and the appreciation of the displayed output signal. In this report, we will be throwing more light on how these were materialized .
REQUIREMENTS
1. CD/HEF4046 IC
2. A voltage regulator
3. An Oscilloscope
4. 100 Resistors
5. Cupper cables
6. Mother board
7. Capacitors
                                    CIRCUIT CONSTRUCTED

 ![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/8a6a3d4c-8222-4368-ad0c-10b5cc9247f5)

                                   #RESULTS
VCO in 0.2 0.3 0.4 0.5 0.6 0.7 0.8 0.9 1.0
VCO out 3.56 3.49 3.48 3.46 3.45 3.43 3.41 3.39 3.37
Frequency 10 10 10 10 10 10 10 10 10

                                 #OBSERVATIONS
As in the case with the PLL , the frequency of the input and output signal is the same.
As the voltage of the input signal increases, that of the output signal reduces due to the presence of the resistors and the fact that part of the output is used at the input signal
PRECAUTIONS
The circuit should be constructed as indicated on the diagram and simulated
The corresponding channels on the voltage regulator that can produce the required input voltage values should be used

                                 #Simulation
The PLL has gained enough applications in power systems operations and this could be found in 3 phase grid connected inverter. You are required to draw this schematic in SIMULINK. For us to send a current into the grid, the current must be in phase with its voltage. The PLL is used in this case to generate a reference voltage which must be in phase with actual voltage. This is to ensure that any alterations in the actual voltage can be traced and brought to normal by the reference voltage from the PLL. The same principle applies when we want to send reactive power to the grid, we use PLL.
You are expected to show on the oscilloscopes how the voltages of the reactive and active components of the grid currents are in phase with the reference voltage from the PLL.

Simulink Diagram
![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/60d1e119-eb86-4acb-9036-581eb2d8a0fb)

Scope output Waves
![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/595906f0-4872-4336-9a5b-682dbb5300ae)

![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/b8e15384-0c2f-4e59-b354-28896ae3fc00)

![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/c74b8432-1e76-4fab-8c56-313fe9f4eecb)

![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/2a6c5489-e2ef-41c9-8390-89c7923da00c)

![image](https://github.com/AlkaloidWells/FeedbackSystems/assets/55930366/1374adf1-74ae-4764-8451-66865ea222fb)


                                 #CONCLUSION
The PLL is a very important circuit due to its wide range of applications.





 
  
