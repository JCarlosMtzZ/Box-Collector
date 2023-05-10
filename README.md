# Box Collector
This is a Multi-Agent system that consists in a field with spread boxes that robots have to collect and order inside shelves with a maximum capacity of five boxes.

In order to search boxes, the robots choose a direction to keep during certain amount of time while trying to avoid the borders of the field as well as other robots. Once they find a box, they go directly to the wall where the shelves are located to order the boxes, but they have to fill one before going to the next shelf.

This system integrates the Mesa framework and runs a server with the `run.py` file. This server will provide a graphic and live representation of the execution of the system.

The `single_run.py` file executes the system once and provides information about the state of every robot and the boxes at the end of the execution. 
