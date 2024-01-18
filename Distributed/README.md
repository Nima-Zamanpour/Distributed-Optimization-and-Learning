This folder contains ('.ipynb') files for the distributed project.

This project aims to let agents reach a consensus on where to take a pre-determined formation while avoiding obstacles. This is an optimal control problem as the acceleration inputs should also be minimal. We use dual and ADMM distributed optimization without any coordinator so the agents fuse their data via a communication graph. The simulation is done using four agents and two obstacles.
