# Game-of-Life
Conway's Game of Life, optimized using a divide and conquer approach with CSP-style message passing between worker goroutines.

- main.go - Where channels and goroutines are initialised.
- gol.go - Where the main processing of the Game of Life takes place.
- pgm.go - Where PGM images are written and read.
- control.go - Where a library called 'termbox' is used to intercept all keypresses during execution.
