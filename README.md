# Game-Of-Life

> Python implementation of Conway's Game of Life 🕹️

![Game of Life](https://cldup.com/8Ond27Md0i.png)

Conway's Game of Life is all about simulating real life rules on some random arrangement of cells in a given environment. The rules are as follows.

- Any live cell with fewer than two live neighbours dies, as if caused by underpopulation
- Any live cell with two or three live neighbours lives on to the next generation
- Any live cell with more than three live neighbours dies, as if by overpopulation
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction

The GOL code in this repository follows the glider configuration of the game. Just run the `main.py` file using the following command and you should see a turtle graphics window with some random arrangement of cells first and the board should be "alive" after that.

```bash
python main.py
```