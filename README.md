That allow create computers with much lower power consumption.


***NXOR Element***

![nxor](https://raw.githubusercontent.com/ValeryAndreevichPushkarev/ReactiveLogicalElements/main/index.jpeg)

If the first two capacitors have different voltages, the voltage on the third capacitor is equal to zero.
In other cases, voltage on other capacitors equals reversed voltage on the first two.

That is an equivalent of the NOT (XOR) element. (or A&!B is we use mosfet in output cascade)

For 1 pF at 10 mV and 0,01 Ohm wire resistance switching time is about 5*tau, or 50 femtoSeconds.

Power consumtion (maximum) is not grater that t*U^2/r, or less that 0,5 fJ.


TODO: 
Try to represent positional encoding with C=A&!B functions and OR operation implemented with merge transistors current (n transistors in parallel that drived by capacitor scheme).

Read about Quantum Well.

Define initial states.

Make simulations with charge-based logical elements.
They consist of a few stripes of n-semiconductors, surrounded by metal stripes of input signals.

How did they perform logical functions?
First of all, all semiconductor stripes are in an external electric field that defines the initial state of the logical element. 
After metal stripes change their potential, charges in n-semiconductors "start to move".
(OR element - two parallel metal stripes with semiconductor between them.
AND element - about the same, with the help of an external electric field it is possible to move charge from bottom to center of semiconductor with one input, and from center to end with second input.)

That allows to perform more power-efficient computations, than traditional TTL (no switching power dissipation) with awesome speed (almost no "gate capacitance", all stripes has air gap between them, that reduce capacitance)


