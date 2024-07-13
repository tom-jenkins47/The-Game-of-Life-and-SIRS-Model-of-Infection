## The Game of Life ## 

From https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life: 

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states,\
live or dead (or populated and unpopulated, respectively). Every cell interacts with its eight neighbors, which\
are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

- Any live cell with fewer than two live neighbours dies, as if by underpopulation.
- Any live cell with two or three live neighbours lives on to the next generation.
- Any live cell with more than three live neighbours dies, as if by overpopulation.
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every\
cell in the seed, live or dead; births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick.\
Each generation is a pure function of the preceding one. The rules continue to be applied repeatedly to create further generations.

#### Run the code GOLSimulate.py and follow the prompts to either simulate the GOL on a defined grid size, or collect data relating to the evolution of the system over time. If using the Spyder IDE, ensure the plotting backend is set to automatic. ####

## The SIRS Model of Infection ##

From https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology:

The SIRS model is one of the simplest compartmental models, and many models are derivatives of this basic form. The model consists of three compartments:

- S: The number of susceptible individuals. When a susceptible and an infectious individual come into "infectious contact", the susceptible individual contracts the disease and transitions to the infectious compartment.
- I: The number of infectious individuals. These are individuals who have been infected and are capable of infecting susceptible individuals.
- R for the number of removed (and immune) or deceased individuals. These are individuals who have been infected and have either recovered from the disease and entered the removed compartment, or died. It is assumed that the number of deaths is negligible with respect to the total population. This compartment may also be called "recovered" or "resistant".

This model is reasonably predictive for infectious diseases that are transmitted from human to human, and where recovery confers lasting resistance, such as measles, mumps, and rubella.

#### Run the code SIRSSimulate.py and follow the prompts to either simulate an outbreak of infection on a defined grid size, or collect data relating to the evolution of the system over time. The code also allows the user to define separate probabilties of susceptibility, infection and recovery - which greatly influences the behaviour of the system. If using the Spyder IDE, ensure the plotting backend is set to automatic. ####



