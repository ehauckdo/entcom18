# Monte Carlo Tree Search (MCTS) modifications

This repository contains two modifications to the MCTS algorithm used in the sample controller provided by the General Video Game AI Competition (GVG-AI).

## Redundant Action Avoidance (RAA)

Identify actions that can nulify one another at the first step of the game and decrease the chances of executing such actions during rollouts.

## Non-Defeat Policy

Change the recommendation policy by performing a 1 step verification from the root node and eliminate children whose state is a loss.
