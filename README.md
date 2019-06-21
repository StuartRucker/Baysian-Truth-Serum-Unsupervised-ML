
# Baysian-Truth-Serum-Unsupervised-ML
Using the Baysian Truth Serum to create an Unsupervised Machine learning algorithm based on units which indepentently maximize mutual inforamation. This project was developed in the MIT Sloan Neuroeconomics Lab by [Drazen Prelec](https://economics.mit.edu/faculty/dprelec) and [Stuart Rucker](stuartrucker.github.io).

## Background Theory:
BTS is a scoring system for eliciting and evaluating subjective opinions from a group of respondents, in situations where the user of the method has no independent means of evaluating respondents’ honesty or their ability. It leverages respondents’ predictions about how other respondents will answer the same questions. Through these predictions, respondents reveal their meta-knowledge, which is knowledge of what other people know. 

Key Publications:

 -  [Prelec, D., Seung, H.S., and McCoy, J. “A solution to the single-question crowd wisdom problem.” Nature, 2017, 541, 532-535.](http://www.nature.com/nature/journal/v541/n7638/full/nature21054.html)
 - [Prelec, D. “A Bayesian truth serum for subjective data.” Science, 2004, 306, 462-466.](https://nelmit.files.wordpress.com/2016/10/bts.pdf "bts")
 - [Prelec, D. “Introspection and Communication: A Game-Theoretic Approach.” Harvard Business School. April, 1987, 88-032](https://nelmit.files.wordpress.com/2016/10/introspection_and_communication_a_game_theoretic_approach_prelec.pdf "Introspection_and_Communication_a_Game_Theoretic_Approach_Prelec")

## Project Theory:
This project applies this scoring system to individual neurons within a neural network to build an unsupervised learning module that is less computationally expensive and more modular than other approaches.

PDFs describing the approach Mathematically:

 - [Basic Theory](https://github.com/StuartRucker/Baysian-Truth-Serum-Unsupervised-ML/blob/master/theoretical%20notes%20pdfs/BTSAlgorithm.pdf)
 - [Theory Applied to Datasets of Images](https://github.com/StuartRucker/Baysian-Truth-Serum-Unsupervised-ML/blob/master/theoretical%20notes%20pdfs/BTSNMarch23EntropicFormulation.pdf)

**Figure:** Weights of the network are maximized using gradient descent. Each grouping of red, greed, blue, and purple bars represents the way one of 4 output nodes responds to one of the 8 stimuli. Notice how each of the four output nodes (red, green, blue, purple) responds differently to the inputs. This is because each output node is working to maximize the information that it conveys, leading to perfect mutual information between the 4 outputs and 8 inputs)] 
![enter image description here](https://i.imgur.com/MUQRnXS.gif)

## Important Files


