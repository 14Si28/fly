## Planning a search

By the help of planning search we can generate a great flight plan.

Planning is the core capability of aerial vehicle like we do in our everyday life.

Solving a planning problem is reduced to search space and once you define your search space you start with 
search on that search space.

A flight plan is the sum of series of action taken from some initial location to some goal location to reach safely.

Say for example one vehicle has to travel through 2 points, rather than defining the smooth path from initial to final 
state, we can defide the initial to final state into decreate set of states (actions).
Each type of actions has its own cost which decides how easy the task is to exicute.

To have a search space, you must have
* All possible state
* Start state
* Goal state
* Actions
* Cost
