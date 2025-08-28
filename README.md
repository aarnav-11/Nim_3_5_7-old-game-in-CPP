# Nim 3-5-7 (Console)

Two-player take-away game on three rows of sizes 3, 5, and 7.

- Players alternate turns selecting a row (1–3) and a block number; the code fills all cells in that row up to the block. Each row can only advance forward.
- The player who makes the final filling move (all 15 cells filled) wins.
- This is equivalent to classic Nim with heaps [3, 5, 7].

## Layout
Row 1: 3 cells
Row 2: 5 cells
Row 3: 7 cells

## Files
- `Nim_3_5_7/main2.cpp`: Active playable version with simple console UI.
- `Nim_3_5_7/main.cpp`: Earlier commented draft.
- `Tic_Tac_Toe.xcodeproj`: Xcode project (kept as-is); build/run from this project or compile `main2.cpp` directly.

## Build (CLI)

g++ -std=c++17 Nim_3_5_7/main2.cpp -o nim && ./nim

## Notes
- Author: aarnav-11 <aarnav11@g.ucla.edu>
