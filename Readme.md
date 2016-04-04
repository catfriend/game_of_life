This is my version of John Conway's Game of Life, created with HTML, CSS, and JavaScript. Information on John Conway, the Game of Life, and cellular automata can be found with a web search. In this version one can choose a random selection to begin, or fill in cells as they please, and then click start. The cells will then animate and die, according to the rules:

1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overcrowding.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.