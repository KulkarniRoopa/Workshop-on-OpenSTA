# Workshop-on-OpenSTA
This contain the theory and lab sessions related to the STA and the tool usage to perform Static Timing Analysis

Static timing analysis (STA) is a method of validating the timing performance of a design by checking all possible paths for timing violations. STA breaks a design down into timing paths, calculates the signal propagation delay along each path, and checks for violations of timing constraints inside the design and at the input/output interface.

How does STA work?

When performing timing analysis, STA first breaks down the design into timing paths. Each timing path consists of the following elements:

Startpoint. The start of a timing path where data is launched by a clock edge or where the data must be available at a specific time. Every startpoint must be either an input port or a register clock pin.
Combinational logic network. Elements that have no memory or internal state. Combinational logic can contain AND, OR, XOR, and inverter elements, but cannot contain flip-flops, latches, registers, or RAM.
Endpoint. The end of a timing path where data is captured by a clock edge or where the data must be available at a specific time. Every endpoint must be either a register data input pin or an output port.

Tools Used:
OpenSTA is a distributed software testing architecture designed around CORBA, it was originally developed to be commercial software by CYRANO. The current toolset has the capability of performing scripted HTTP and HTTPS heavy load tests with performance measurements from Win32 platforms. However, the architectural design means it could be capable of much more.
