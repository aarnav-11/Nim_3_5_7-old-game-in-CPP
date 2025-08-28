# Nim 3-5-7 (Console)

This is a cool project I built after 15 days of coding and iteration. It implements the classic Nim puzzle in a simple console interface.

- Players alternate turns selecting a row (1–3) and a block number; the code fills all cells in that row up to the block. Each row can only advance forward.
- The player who makes the final filling move (all 15 cells filled) wins.
- This is equivalent to classic Nim with heaps [3, 5, 7]. See: Nim (Wikipedia): https://en.wikipedia.org/wiki/Nim

## Layout
Row 1: 3 cells
Row 2: 5 cells
Row 3: 7 cells

## Files
- `Nim_3_5_7/main2.cpp`: Active playable version with simple console UI.
- `Nim_3_5_7/main.cpp`: Earlier commented draft.

## Build (CLI)

g++ -std=c++17 Nim_3_5_7/main2.cpp -o nim && ./nim

## Notes
- Author: aarnav-11 <aarnav11@g.ucla.edu>
