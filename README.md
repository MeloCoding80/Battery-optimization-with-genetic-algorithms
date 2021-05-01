# Battery-optimization-with-genetic-algorithms
Optimization of a customer's owned battery to take advantage of volatile electricity market prices

The objective is to model and optimize a system composed of: 
- an electricity consumer
- a battery
- solar panels
- a grid

The only componenent over which we will have control is the battery. By optimizing its daily charging and discharging cycles, we will be able to take advantage or avoid high electricity prices, with this simple principle: 
- when electricy is cheap on the market, we will buy more electricity from the grid that what is needed by the consumer, and store the excess in the battery
- when electricity is expensive, we will consume the electricity previously stored in the battery instead of buying from the grid. In certain cases, we will even be able to sell electricity on the market.

This optimization will result in a lower electricty bill at the end of the day.

For further details and explanations, please refer to the Python Notebooks.
