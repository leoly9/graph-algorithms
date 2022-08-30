# Graph Algorithms

This repo contains the last project for "Large-scale Social and Complex Networks: Design and Algorithms" UCLA class. Part 1 and Part 2 use real data obtained from Yahoo Finance and Winter 2019 Uber traffic data. Part 3 simulated a Operations Research problem.

## Part 1 - Stock Market

In this part, we attempt to study data from stock market as a graph. In particular, we study correlation structures among fluctuation patterns of stock prices using tools from graph theory. It derives from the intuition that investors utilize similar strategy within the same economic factors/ sectors.

We constructed graphs based on similarities among the time series returns on different stocks at different time scales (day vs. a week). 

## Part 2 - Uber Dataset

Uber contains a vast amount of statistics about transportation dynamics. In this part, we took a deep look into traffic movement in 2019 Quarter 4, Los Angeles area. 

We first analyzed the current traffic flow by mapping it into a Traveling Salesman Problem. We then optimized traveling time by constructing simulated roads using Dijsktra's algorithm.

## Part 3 - Multi Depot Capacitated Vehicle Routing Problem

In this part, we try to find the optimal route and optimal vehicle distribution given demand for each major Indian city and a limited amount of trucks. The main objectives/ constraints of the task are: 
1) minimizing the distance, 2) carry all goods that satisfy the cities' demands, 3) without overloading the truck (rolling total carried goods <= truck capacity). 
