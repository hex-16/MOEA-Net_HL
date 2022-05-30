# Multi-Objective Evolutionary Algorithm for Networks with Heterogeneous Loads

> MOEA-Net$_{HL}$ for short

The relevant codes of our work ["**Enhancing Robustness and Transmission Performance of Heterogeneous Complex Networks via Multi-Objective Optimization**"](https://ieeexplore.ieee.org/abstract/document/9523789). 

**Published in:** [IEEE Systems Journal](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4267003) ( Volume: 15, [Issue: 4](https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=9645394), Dec. 2021)

# Requirements

- python 3.7
- networkx
- pandas
- numpy

# Run the demo

- For BA scale free networks' optimization.

```console
python CN_Run_MOEA_SFCN.py
```

- For real networks' optimization.

```console
python CN_Run_Real.py
```

# Code Description

- `CN_Basic.py`: implements the basic functions of host-router like communication networks.
- `CN_Run_MOEA_SFCN.py`: implements the optimization process of communication networks.
- `CN_Run_Real.py`: implements the optimization process of realistic communication networks.

# Data Description

- `/data/USAirLines.txt`: topology of US air lines
- `/data/as19981229.txt`: topology of AS-level network (AS for Autonomous Systems)

# Dataset Ref

- US Air lines: http://vlado.fmf.uni-lj.si/pub/networks/data/
- Autonomous Systems : graphs of the internet: http://snap.stanford.edu/data/