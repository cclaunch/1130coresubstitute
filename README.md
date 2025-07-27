1130 Core Substitute

This project is intended for IBM 1130 systems where a core memory compartment is nonfunctional and unlikely to be restored to reliable operation. The printed circuit board is inserted at the top of the core compartment and is connected via the top cables T1, T3 and T4 that are normally plugged into the SLT board for the compartment. 

It is based around a Magnetoresistive Random Access Memory (MRAM) which provides the same non-volatility as core memory even after two decades sitting without power. MRAM has infinite read and write cycles, unlike flash memory, thus it is very suitable for use in a computer.

One would disconnect the four voltage rails to the core memory compartment (+6, +3, -3 and +12) so that the compartment itself is inert. The new PCB fits in the space at the top of the compartment where the top cables were connected. It requires only a pair of wires to connect it to the +12V rail of the 1130 system. 

This first version was developed for a particular 1130 system I restored, one with 8K of 3.6 microsecond core. This fits in the B gate in compartment C1. The SLT board has a core memory stack mounted in the center and SLT cards arrayed around the outside of the stack to provide the logic to make the core work. 

The same board can be easily enhanced to connect to cable T2, for machines with more than 8K of memory (or any 2.2 microsecond core memory model). Assuming the machine is configured for larger memory sizes so that the proper address lines are implemented in the device controllers and central processor, this single board could implement up to the maximum 32K word memory capacity. I will outline how the enhancement could be accomplished in a document in this repository.
