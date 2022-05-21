**TL01**
**First scenario
 One line and one traffic light
 Control the lights with respect to timing
Model the traffic light system with the following diagram
 Structure: a class diagram that represents the main structural elements
Develop a realistic traffic light control system.
 Use leds as traffic light
 Use an Arduino as μC
 Map the state machine model to code (via switch state pattern)
**

**TL02**
**Extend the (car) traffic light system of the first sprint by a pedestrian light
 Extend a button for the pedestrian. If pressed, the pedestrian lights switches as fast as possible to
green.
 Guarantee that
 The pedestrian lights signal is red if the traffic light signal is green
 If the pedestrian lights signal is green the traffic light is red
 At least the green traffic light is required to stay for 10 time units in green and 5 time units in yellow.
Model your solution
 Extend the class diagram
 Extend the tinkercad simulation by;
 A pedestrian button
 Green and red light for the pedestrian light.
**

**TL03**
**Realize the pedestrian light in concurrent to the traffic
light
 Update your solution on model level in form of using concurrent
regions
**

**TL04**
** Develop an interface for the traffic light systems (TLS)
 The coordination between the traffic lights should consider at least two
different traffic light systems
 Nevertheless, the coordination should be realized in a way that the traffic lights
can be exchanged
 Example: you are 3 teammates (A, B, C) with three different TLS
 The following coordination should be possible:
 A with A
 A with B
 A with C
 B with C
 First, update your state machine model
 The interface can be represented by an appropriate event (e.g. signalizing switching to a specific state (e.g. redStateEvent) of (two) different state machines
 Run the TLS in parallel (You have different possibilities)
 Via different Arduino instances that connected via an appropriate serial interface (UART, I2C, …)
 Extra: Via a network connection (TCP/UDP) via a standard C/C++ implementation (plus 5 points in addition)
 Update your code accordingly**
