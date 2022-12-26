# Multi stage convex optimization problem

Consider a company that operates a fleet of cargo ships. The company wants to optimize its shipping routes and cargo loadings to maximize profits over a planning horizon of T time periods. Each time period t corresponds to a specific month, and the company can choose the routes and cargo loadings for each ship in each time period.

The company faces uncertainty in the form of unpredictable demand for cargo shipping and varying fuel prices. Specifically, the demand for cargo shipping and the fuel prices are modeled as random variables that are drawn from known probability distributions at the beginning of each time period.

The company's objective is to maximize its expected profits over the planning horizon, subject to a number of constraints. These constraints include:

Capacity constraints: Each ship has a maximum cargo capacity, and the total cargo loaded on a ship in any time period must not exceed this capacity.
Demand constraints: The total demand for cargo shipping in each time period must be satisfied.
Budget constraints: The company has a fixed budget for fuel costs in each time period, and the total fuel costs for all ships in that time period must not exceed this budget.
