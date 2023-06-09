# MScA 31009-Machine Learning and Predictive Analytics Final Project

Chess is motivated by the heuristics of many kinds of pieces in diverse and short-term tactics that build into longer-term strategies. This is essential because the advantage of a position is always rooted in the relationships between the rules of the pieces. This makes pattern identification of chess more reliant on understanding how the nuanced and specific positioning of pieces leads to their advantages. 

A CNN can approximate a human-like evaluation of various chess positions based on the patterns it learns without having to calculate ahead. I will consider spatial patterns in the positions, i.e., placement of the pieces on the board. A kernel in a CNN should be able to recognize the spatial data and detect relevant patterns.

Critics of CNNs argue that neural networks cannot adequately explain such tactical advantages because the forms of these conditions are too global across the board and affected by extraneous variables. 
I hypothesize that the CNN will be able to classify approximately 90% of positions correctly.

The neural network must learn to evaluate positions from whites. To obtain predictions for the other player, the board can be flipped, passed to the model, and its prediction reversed again.
