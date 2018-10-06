# 50.002-Computation-Structure

// Minihardware project
The project is to implement and design a 1-bit full adder on a stripboard. FPGA tester is implemented to work automatically tesing all the possible inputs using FSM. It allows both automatic testing and manual testing.

The files inside Mini Hardware project folder are created from io-shield demo project. We have modified mojo_top.luc, seven_seg.luc and also created counting.luc as a frequency counter and custom.ucf as constraints for custormized input sum, carryout and output a, b, carryin.
Finite state machine is used in this project to toggle between test states, it will only pass to the next state once the conditions are met.
