# PCB-Design-for-Audio-Mixer
Designing a PCB schematic diagram for an FPGA based audio mixer which has 4 input channels each of 16 bits. Each of these input channels are multiplied by different gain factors each of 10 bits for the target channel. Additionally, each channel is also multiplied by master volume control. These target channels are the sum of weighted input channels and are then sent as a TDM stream to generate a 24 bit output.