# 104th Santa 2023 - The Polytope Permutation Puzzle solution 

## Evaluation
A permutation puzzle comprises a solution state, an initial state, and a set of allowed moves.

The solution state and initial state are arrangements of symbols we call colors, while the moves for a puzzle correspond to certain permutations of these arrangements.

A sequence of moves solves a puzzle if applying each permutation in the sequence to the puzzle's initial_state results in the puzzle's solution_state, and we call such a sequence a solution to the puzzle.

Additionally, a few of the elves have discovered that they can rearrange some of the stickers on a puzzle instead of applying moves, and so a puzzle may also be allotted wildcards. In this case, the resulting state may differ up to the puzzle's num_wildcards and the sequence will still be considered a solution.

The overall score for a submission is the total number of moves in all of its puzzle solutions. The goal of the competition is to solve all of the given puzzles in the fewest moves.

You may view the evaluation metric here: Santa 2023 Metric.

## References
- Current Best Submission : https://www.kaggle.com/code/isaienkov/current-best-submission
- Solve All NxNxN Cubes w Traditional Solution State: https://www.kaggle.com/code/seanbearden/solve-all-nxnxn-cubes-w-traditional-solution-state
- [A-Star Algorithm] Polytope Permutation: https://www.kaggle.com/code/whats2000/a-star-algorithm-polytope-permutation