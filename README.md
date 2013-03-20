marchmadness
============

Python script to generate march madness brackets from probability input (as in the format of the 538 data from Nate Silver's blog).

Probabilities are assumed to be the probability that each team will reach each corresponding round, after many rounds of modeling. My script then calculates a conditional probability for each head-to-head calculation.

Features
--------
Run ./predict.py -h for a list of help options
* Generate a "quick-pick" bracket (no flag needed)
* Run many simulations and model the likelihood of each team winning the championship (--champion_mode)
* Run simulations until a specific, desired champion is found (--find_champion)
