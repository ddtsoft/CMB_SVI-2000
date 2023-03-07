# CMB_SVI-2000
A small design of a interfacce between Commdore 8-bit computer or simular and SpectraVideo SVI-2000 robotic arm.

The interface are inspiered by the re-enginered picure from an origin interface for the SVI-2000 robotic arm for Combodre 8-bit copmuters, the jpg picture. The major difference between the two solutions are the decoder and use of a on/off signal. This is added so the design can be used with other computers that have a GPIO or simular solution with 5 free pins, or even 4 pins and manual control of the activation pin, do note the decoder uses signal from 0000 to 1111 where any signals above 1001 are not decoded to movement, thus the need of the activation signal.

The robotic arm are controlled using two ATARI style joysticks and the arm have 5 axis of movment, without any returnsignal to the computer. This is a cost reduction solution and due to restrictions in the origin design from SpectraVideo, but also so the robotic arm can be used in stand alone mode, controling the momvents using only two ATARI type joysticks.


The are no licens restrictions on this work so feel free to share are inprove if needed.
