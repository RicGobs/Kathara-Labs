# 03-L2_Flooding_Flood_Others
Original network scenario can be found [here](https://github.com/nsg-ethz/p4-learning/tree/master/exercises/03-L2_Flooding).
There, you can find a detailed explanation about the scenario, and the exercise (here only the solution is provided).

## Network Scenario

This is the network scenario topology: 

![topology](images/l2_topology.png)

It is composed by four hosts `hx` and one switch `s1`. 
The switch act as a repeater. 

## Testing the scenario
1. To run the network scenario, open a terminal in the scenario directory and type: 
```bash
kathara lstart 
```

2. For testing the P4 program, open a terminal on one host and ping the others: 
```bash
root@h2:/# ping 10.0.0.1 
```

3. If all the hosts can reach the others, the switch is working. 
