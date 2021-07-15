That allow create computers with much lower power consumption.


***NXOR Element***

![nxor](https://raw.githubusercontent.com/ValeryAndreevichPushkarev/PassiveReactiveXORElement/main/index.jpeg)


If the first two capacitors have different voltages, the voltage on the third capacitor is equal to zero.
In other cases, voltage on other capacitors equals reversed voltage on the first two.

That is an equivalent of the NOT (XOR) element.


***NAND Element***
![nand](https://raw.githubusercontent.com/ValeryAndreevichPushkarev/PassiveReactiveXORElement/main/nand.jpeg)

***NOT Element***
![nxor](https://raw.githubusercontent.com/ValeryAndreevichPushkarev/PassiveReactiveXORElement/main/not.jpeg)


For 1 pF at 10 mV and 0,01 Ohm wire resistance cut off frequency is about 5*tau, or 50 femtoSecond.

Power consumtion (maximum) is not grater that t*U^2/r, or less that 0,5 fJ.


TODO: Make OR, NOT elements. Make precision power consuption calculations. Make dual scheme (while first restore initial charges, the second scheme is working). Make script that generate electic net based on those elements. Well, read about Quantum Well.

