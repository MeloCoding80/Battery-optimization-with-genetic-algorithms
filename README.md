# Battery-optimization-with-genetic-algorithms
Optimization of a customer's owned battery to take advantage of volatile electricity market prices

The objective is firstly to model the following system :

image.png

At a given time, the values of these energy exchanges depend on different factors:

PV output
Load amount (corresponds to the energy consumed by the client)
Battery's state of charge
Grid consumption setpoint
We don't have any control on the PV output and on the load. The priorities are:

At each time, the required load has to be satisfied.
The self-consumption of the PV energy output has to be maximized (we will try never to sell PV energy to the grid)
The most important component here, and the only one over which we have control, is the battery. The battery has certain operating constraints that have to be respected, otherwise it can be severely damaged:

Maximum charging power Pmax
Maximum and minimum states of charge (SOCmax and SOCmin)
