Q1A :  20/20  -- :thumps up:

Q1B :  10.0/10.0  -- Minor note: the observations shrink towards the overall mean, not the towrads the prior. The idea is that the flexibility in the prior's hyperparameters means the that the prior moves to match the observed data

Q1C :  16/20  -- The model _does_ take review uncertainty into account. Reviews that are less certain experience more shrinkage and thus thier original value weighs less in the overall average

EC :  1.5/2.0  -- You propose a stong model, but go a bit overboard in assuming parameters from the data. A better model would admit uncertainty in those values (since the data are uncertain after all) and put priors over them. Then the data and variations in it can speak for itself.
