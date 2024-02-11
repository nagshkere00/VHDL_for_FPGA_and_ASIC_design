Lab 1: Creating first VHDL design and simulating the design:
Design inputs:
1) current_temp , a 7 bit vector, as an input
2) desired_temp, a 7 bit vector, as an input
3) display_select, a signle bit
Design output: 
1) temp_display.

The logic we want is that if the display_select is a '1' we want to put current_temp out on temp_display, but if the display_select is a '0', we want to put desired_temp on the output temp_display.
Creating an entity and architecture for the lab 1.   

Q: What will be the basic structure of you design, and how will you get the VHDL design to accomplish the objectives?

Lab 2:
Design inputs and outputs:
1) Add 2 new outputs to our entity ,  A_C_ON , and FURNACE_ON.
2) Add logic for determining when the A_C_ON and FURNACE_ON are '1', and when they are '0'.
3) Create a testbench to verify design operates logically correct.
4) Verify in the testbench the display_out , the a_c_on, and furnace_on.
5) The testbench should sequentially test the correct operation of each output.

Q: How will lab 2 be implemented to add the functionality of controlling the A_C_ON and the FURNACE_ON outputs with the added input COOL and HEAT?

Lab 3: RTL
Design inputs and outputs:
1) Start with a copy of the previous lab.
2) Add registers to the inputs.
3) Create internal signals for the registered input values.
4) Register the outputs.  You can either put the combinatorial logic in a clocked process, or keep the combinatorial process for the logic and add a clocked process for registering the outputs.
5) Generate a clock in the test bench.    If needed, generate a reset in the test bench.
6) Simulate your design and verify the flip-flops are behaving correctly.

Q: How will you add the registers(flip-flops) to the inputs and outputs, and keep the functionality the same. Also what changes will you need to make to the testbench in order to operate the flip-flops correctly?

Lab 4: VHDL types
Q: How will you incorporate a state machine to control the outputs in your design.

Lab 5: VHDL operators
Q: How will you add a counter to the design and have it interact with the state machine?

Lab 6: Verification
Using lab 5 add some assert statements to the test bench to verify correct operation of the system by observing the outputs.

Q: How can you check that a signal has the right value at a specific time during simulation with our testbench?
