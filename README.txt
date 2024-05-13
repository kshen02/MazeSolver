This program can either :
	- load a maze from a txt file
	- or generate a random maze of the given size
and animates a robot (represented by a green triangle) to find the way from start position to exit.

To set the size for the random generated maze, you may edit the MAZE_WIDTH and MAZE_HEIGHT variables.
To set the block width, you may edit the BLOCK_WIDTH variable.

To run the program with example maze from "maze_structure.txt" file:
	- set both the MAZE_WIDTH and MAZE_HEIGHT to 11
	- comment out line 288 in main.c
	- uncomment line 287 in main.c
	- run the program!

To run the program with a random generated maze:
	- comment out line 287 in main.c
	- uncomment line 288 in main.c
	- edit the maze size if you like
	- run the program!

* If you are loading the maze from txt files, you will have to configure MAZE_WIDTH and MAZE_HEIGHT before executing the program.

---------------------------------------------------------------------------------------------------------------------------------------------------------

To execute the program, type in the following commands in the terminal:

	gcc main.c graphics.c
	./a.out | java -jar drawapp-2.0.jar