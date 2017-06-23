# ChaosTag
Riddler from June 17th: https://fivethirtyeight.com/features/how-long-will-chaos-reign-in-this-game-of-tag/

My Analytic Solution: 
Expected number of tags for N players = 2^(N-1)-1

This repo is a numerical test of this analytic expression.
The code lives in Chaos_Tag.ipynb.
I track the active and inactive players, as well as who has tagged whom.  This allows me to activate inactive players when their tagger has been tagged.
The plots are histograms of 16000 simulated games with N = {3,10} players.


