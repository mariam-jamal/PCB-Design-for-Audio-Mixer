# PCB-Design-for-Audio-Mixer
Designing a PCB schematic diagram for an FPGA based audio mixer which has 4 input channels each of 16 bits. Each of these input channels are multiplied by different gain factors each of 10 bits for the target channel. Additionally, each channel is also multiplied by master volume control. These target channels are the sum of weighted input channels and are then sent as a TDM stream to generate a 24 bit output.

FPGA design and development:

● Input:

    4 channels: 16 bit Serial TDM, 48kHZ Frame Rate
  
    Format: 1.15 fixed point, signed

● Output
  
    2 channels: 24 bit Serial TDM, 48kHZ Frame Rate

    Format: 1.23 fixed point, signed
    
● Gain Controller:
     
    -30dB to +30dB
    
    Format: 5.5 fixed point, unsigned
    
● Master Volume Controller:

    -30dB to +30dB
    
● Total number of multiplier instances = 2

System Architecture Block Diagram

![image](https://user-images.githubusercontent.com/30799589/132218456-c5f60615-dbf6-4647-af34-ee3fa9119a3b.png)

Project Task

1. Defining the project and initial design idea development through a block diagram
2. Research and selection of component/s
3. Cost Management of Project
4. Reading and understanding the datasheet
5. Setup of PCB design environment (Circuit Maker)
6. Schematic Design and Footprint of a component
7. Overall Layout and Schematic Diagram
