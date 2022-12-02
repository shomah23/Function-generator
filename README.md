# Function-generator
A function generator is a electronic device that can produce a variety of different waveforms. The one we will build can output square, triangle, or sine waveforms. Like standard function generators, the circuit allows for frequency adjustment; we get ours through a potentiometer. The circuit can also easily allow for amplitude adjustment
# how to build a Function generator
equipment:

LM324 op amp chip

2 10KΩ resistors

4 100KΩ resistors

22KΩ resistor

220KΩ resistor

1μF ceramic capacitor

33nF ceramic capacitor

10nF ceramic capacitor

100KΩ potentiometer

# Build the circuit
before we begin to build the circuit first we need to test it on any website we can make a circuit on it. it is many but I'm using either TinkedCad or iCircuit as shown in the next figure:
![8a852ae3-c4c3-4272-ac8b-05796e4bfd5c](https://user-images.githubusercontent.com/109688999/205280013-3418afb1-ef1d-4f13-a46e-489158adfadd.jpg)
                                                       figure 1.1
                                                       
we could generate the functions so we are ready to start!

![c7a2fc9f-dff6-405e-9be2-3fd01c4d639e](https://user-images.githubusercontent.com/109688999/205281977-2748e5a8-108b-4df0-806e-71b0ff7ffc6e.jpg)
figure 1.2

as shown in figure 1.2 this is the circuit we built. notice that we replaced the 3 op amps with "IC LM324" The IC we used is contain four Op Amps and we are using three of them. One is an oscillator and the others are integrators. Pin 4 and 11 are power pins as shown in figure 1.3

![2022-12-02 (2)](https://user-images.githubusercontent.com/109688999/205282690-0b3a3542-64fd-464f-9707-00d6cc965378.png)

# Results

![d8ea9504-9de8-4a3b-abcd-67d2e22dc0b1](https://user-images.githubusercontent.com/109688999/205285189-9e5482ac-1544-4605-b1eb-717054eb6a22.jpg)
Figure 1.4

![0addee1c-acc8-4d12-8b7b-85a1b46689ab](https://user-images.githubusercontent.com/109688999/205285594-71ce093f-10c2-4a2e-8b6c-cf925b8ba3ae.jpg)

Figure 1.5

first in Figure 1.4 we produced square and triangular waves, in Figure 1.5 we produced triangular and sin waves

# proplem we faced

-The 33nF capacitor value didn’t make the circuit work well so we changed it to 460nF.

-and we tried to make new circuit and tried soldered it as shown in Figure 1.6:

![31771443-4ded-41d2-a091-8c13b3c4ce1e](https://user-images.githubusercontent.com/109688999/205287369-779b4f83-51f3-4cb6-9047-7839fe67b750.jpg)

we tried to solder the IC even thought we knew it was kinda hard, so we ended up by burn it

# References

- http://www.learningaboutelectronics.com/Articles/Function-generator-circuit.php

- https://www.electronics-notes.com/articles/test-methods/signal-generators/function-generator.php




