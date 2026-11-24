# Network Flow Optimization

A Python project developed for my Artificial Intelligence course at UNT. It uses hill-climbing search to increase network flow while respecting edge capacities and flow conservation.

## Features

- Heuristic calculation using residual capacity.
- Successor generation and hill-climbing search.
- Random directed graph generation.
- Flow conservation and capacity validation.
- Comparison with the Edmonds-Karp algorithm.

## Results

- Achieved a total flow of 14 in the provided test case.
- Matched the Edmonds-Karp result of 8 in a tested 30-node network.
- Tested 30 graphs per connectivity setting.

| Connectivity | Average Flow |
|---|---:|
| 3 | 5.47 |
| 2 | 3.00 |

## Technologies

Python, NetworkX, Matplotlib, Google Colab

## What I Learned

This project helped me understand heuristic search, graph algorithms, network optimization, and the relationship between network connectivity and flow.
