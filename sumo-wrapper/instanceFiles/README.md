# Instance format

```Line   1: Instance name
Line   2: Path containing the network and route files
Line   3: Total number of intersections (nI)
Line   4: Total number of phases considering all intersections
Line   5: <intersectionID_1> <numberOfPhases (nP_1)> <p-1-1, ..., p-1-nP_1>
Line   6: <intersectionID_2> <numberOfPhases (nP_2)> <p-2-1, ..., p-2-nP_2>
...
Line nI + 4: <intersectionID_nI> <numberOfPhases (nP_nI)> <p-nI-1, ..., p-nI-nP_nI>
Line nI + 5: Number of vehicles
Line nI + 6: Simulation time (seconds)
```