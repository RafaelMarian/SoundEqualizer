Sound Equalizer Project
1. Project Objective

The objective of this project is to develop a sound equalizer to run on FPGA, utilizing tools provided by Xilinx. The implementation will be carried out using VHDL and C Embedded languages.

2. Resources

    Zybo Development Board
   
    VGA Monitor
   
    Speaker System
   
    Vivado 2022.1 – VHDL
   
    Vitis SDK 2022.1 – C Embedded
   
    Octave or MatLab
   
    Tera Term

4. Hardware Implementation

    Implementation of the Vivado Block Diagram
   
    VGA Video for a resolution of 1980x1080px
   
    Integration with Vitis SDK

6. Software Implementation

    State machine design
   
    Volume adjustment

    VGA values
   
    Noise addition
   
    Exponential Moving Average (EMA) Filter
   
    Audio storage – 3 seconds
   
    Audio playback

8. Results

    First part of the state machine: Increase – Decrease – Reset Volume
   
    Second part of the state machine: Audio storage and playback – 3 seconds
   
    VGA Video implementation
   
    Results of VGA Video implementation
   
    VGA Logic for a resolution of 1980x1080
   
    Last part of the state machine: Noise addition
   
    Signal filtering through the EMA filter

10. Conclusions

The successful development of a sound equalizer using Vivado Block Design and Xilinx SDK, with integration on the Zybo development board and VGA monitor. Implementation of the EMA filter along with the Low Pass Filter.

7. Future Developments

    Expansion of video from 8 bars to 20+
   
    Implementation of additional filters
   
    Transition from VGA to HDMI
