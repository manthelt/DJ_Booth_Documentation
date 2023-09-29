# DJ_Booth_Documentation
This repository serves as documentation and storage for the DJ booth. There are also folders with information on how to control and use the required software to run the lighting effects. There is also documentation on the game room as well if needed. 

## Getting Started
Here is a quick guide to get anyone up and running with the DJ booth

### Required Software

#### QLC+
This is used for controlling the lights Documentation
Link: [https://mixxx.org/](https://mixxx.org/)

#### Mixxx
This is for mixing the input and sending the input into the 
Link: [https://www.qlcplus.org/](https://www.qlcplus.org/)




### General Layout
Here is the layout of the booth and wiring diagram for debugging purposes

[Insert Diagram]

### Turning on the system
To turn on the cabinet use the switch at the top

[Insert Photo of Cabinet].

This will provide power to the entire cabinet of equipment. 

### Audio Playback 

##### Mixer Board
To playback audio use the aux cable connected to the mixer board. The mixer board will allow you to adjust various parameters such as bass, treble, and such. You can also plug multiple inputs into this mixer board for more advanced setups such as using microphones or multiple sources for audio. There is also a headphone output on the mixer board to make it easier to hear the current playback. 

##### Cross-Over
The cross-over allows for filtering of various frequencies for various outputs. Such as filtering out the higher frequencies for the subwoofer and manually adjusting the sub-crossover point. This was added to allow for more control of the speakers and make sure they output the frequencies that won't sound muddy. The crossover we are using has three channels all of which will have the same input going to them which is created using an RCA splitter to allow for proper signal splitting. The outputs of which will go to various amps and subwoofers. For example, the mid will be going to the AMP used for the mid speakers and the sub will be going to a powered subwoofer. Later on, the high channel will be added and this will allow for crisper lyrics in music. The reasoning for having separate amps was to be able to use what we already owned and save some money while still maintaining the best sound quality and volume for social events. This will also allow for more expandability to have speakers outside as well. 

### Light Control
The lights used for this can be controlled through the QLC software and the USB controller. This was to allow for easier saving of configurations for parties. However, a hardwired controller can be used for ease of use if needed and can be daisy-chained into the system later on. The required config files and software are provided in the QLC+ subdirectory in this repository. 
