# Rock-Paper-Scissor

This project is a simple Rock-Paper-Scissor game inspired by Bayesian Inference.

The player's pattern is modeled as the sequence of his/her last few moves, 
while the player's strategy is determined by the last k_s of his/her move, last k_o of the opponent's move, 
as well as greedy factor g and experience factor e.

All four parameters, k_s, k_o, e, g are learnable. k_s and k_o are determined by alternative vote after training, 
while e and g via gradient descent over cross-entropy loss during the process.
