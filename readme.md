
### Main Topic

The application « Radio Mobile Network Tool » is a JavaScript application used for testing and educational purposes. 
The application uses the Leaflet API that provides some tools to manage geographical data.
The objective is then to develop a few extensions of this application to familiarize themselves with radio engineering concepts. 
Therefore, this work consists in developing an extension of a network optimization tool.
In GSM network, one of the main optimization tasks is to define the frequency channel that should be allocated to every station to reduce the interference. 
According to radio coverage of stations, potential interferences between every pair of station is estimated (see project of radio constraints cartography).
In this project, the students should implement a channel allocation algorithm (heuristic, iterative, …) that reduces the number of potential interferences. 
Every station is defined by the number of required channels (depends on the traffic density on the station and is given as an input to the problem).
To that end, the students must define how to evaluate a frequency allocation solution. 
For example, students may consider that two antennas are incompatible if the distance between them is lower than a given threshold D. 
When the same frequency is used by two incompatible antennas, a penalty is applied to the frequency allocation solution. 
The evaluation of a given solution is then the sum of these penalties.
Furthermore, students must implement a procedure for generating an initial allocation solution and a procedure for changing/improving the quality of the current allocation. 
Students may choose one of the known strategies such as: greedy algorithm, local search, simulated annealing, etc. 
The tool must store the best visited solution and display the result.
