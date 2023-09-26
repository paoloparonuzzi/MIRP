# MIRP
Instances and Solutions for the Multi-vehicle Invetory Routing Problem.

Each instance file has the following format:

The first line contains four parameters: the number of nodes including the depot, number of time periods, vehicle capacity, and number of vehicles.

The second line describes the depot and provides: depot identifier (which is "0"), x coordinate, y coordinate, starting inventory level, daily production, inventory cost.

The lines that follow each describes a customer and provides: customer identifier, x coordinate, y coordinate, starting inventory level, maximum inventory level, minimum inventory level, daily consumption, inventory cost.


The format of the solutuion files is as follows:

Day 1
Route 1: 0 – customer ( quantity delivered ) – customer ( quantity delivered ) – … customer ( quantity delivered ) – 0

Route 2: 0 – customer ( quantity delivered ) – customer ( quantity delivered ) – … customer ( quantity delivered ) – 0

¦

Route M: 0 – customer ( quantity delivered ) – customer ( quantity delivered ) – … customer( quantity delivered ) – 0

Day 2

Route 1: 0 – customer ( quantity delivered ) – customer ( quantity delivered ) – … customer ( quantity delivered ) – 0

¦

Route M: 0 – customer ( quantity delivered ) – customer ( quantity delivered ) – … customer ( quantity delivered ) – 0

¦

Day T

Route 1: …

¦

Route M: …

Total transportation cost

Total inventory cost at customer locations

Total inventory cost at the depot

Total cost of the solution (which is the sum of the three terms above)

Processor

Solution time
