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

Run the code GOLSimulate.py and follow the prompts to either simulate the GOL on a defined grid size, or collect data relating to the evolution of the system over time. If using the Spyder IDE, ensure the plotting backend is set to automatic.


