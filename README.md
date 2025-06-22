# cellular-network-dimensioning-using-Erlang-B-formula
This Python script estimates the minimum number of base station cells needed to support a given user density and traffic demand under a specified blocking probability constraint. It uses the Erlang B formula and considers sectoring and frequency reuse to optimize resource allocation in a cellular network.

# -Overview
The program performs the following steps:
Defines the Erlang B formula — to compute the blocking probability based on offered traffic and number of channels.
Uses binary search to invert the Erlang B formula — to determine the maximum supported traffic for a given number of channels and blocking probability.
Evaluates different sectoring configurations (60°, 120°, 180°) — to find the sectoring angle that minimizes the number of cells.
Calculates the number of users and traffic — from area and user density.
Determines channel allocation based on bandwidth and reuse factor.
