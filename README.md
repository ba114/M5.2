ECU definitions for BMW E36 318i with the M44 engine.

This is the development repository for identifying new maps in the Bosch M5.2 DME utilised in the E36 318i/s and Z3.

The processor used in this DME is and Intel 87C196KN which is a CMOS MCS® 96 Microcontroller.
For disassembly in IDA, the processor should be set to Intel 80196 (https://en.wikipedia.org/wiki/Intel_MCS-96)

This repository will primarily be focussing on:
ECU: 0261203667
SW: 40
However SW 34 has been added.

Additionally, definitions have now been created for 0261203668 (USA) DMEs. These are NOT cross compatible. Do not flash a 667 full read onto a 668 DME (or vice versa) as it will not work.

All verified contributions are welcome. The biggest help to this process would be anyone that is able to disassemble the code and identify the routine for EWS delete.

If my work proves helpful to you, donations are appreciated.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?hosted_button_id=TFWBHH4WEEHAU)
