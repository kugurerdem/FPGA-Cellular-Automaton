# What is this?

This is a project where I have built a cellular automata to Basys3 FPGA. A [cellular automata](https://en.wikipedia.org/wiki/Cellular_automaton) is basically a model consisted of cells that are neighbour to each other. When executed, each step of the cellular automata is determined by a set of rules with respect to these cells being on or off. [Conway's game of life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) is one of the most known examples of a cellular automata.  

This was an assignment from a computer science course called Digital Design. What this program is supposed to do is described in the file CS223Project_v3.pdf, the cellgroups and rules that are determined by my ID number can be seen in the files myCellGroups.png and myRules.png, furthermore, the block diagrams, high level state machine structure and block explanations that I have used making this program are presented in the file CS223 Project Report.pdf


# How to run it?

To physically run this, you need the fpga Basys3, and Vivado's program to program it. First open the project.xpr file, then connect your Basys3 into computer. Open the hardware manager and click open the target -> auto-connect. Then right click xc7a35t_0 and select "program it", now you must be able to physically run our cellular automata through the FPGA.

# Demonstration

![images](/images/fpga.jpeg=200x120)

To run 
