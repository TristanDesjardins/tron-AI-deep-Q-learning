# tron-AI-deep-Q-learning
Tron AI using deep reinforcement learning (deep Q learning) with pytorch and pygame. Project done in my free time as a challenge. <br/> 
Probably the hardest one of all the AI projects I've done so far.
Defining a relevant game state even for such an easy game is pretty hard. <br/> 
Making an AI capable of dodging obstacles is not too hard, but actually using strategies to beat the enemy is another thing. I'm really happy with the results. The AI can actually play very well and beat me sometimes. Enjoy! :blush: 

## Preview 
Just run the 'trongameai.py' to see two different AI training and playing against eachother. 
Here's our AIs after a few hours of training : 

## Preview 
**training phase** <br/> **AI vs. AI**       |  **After training**  <br/> **AI (blue) vs. myself (red)**
:-------------------------:|:-------------------------:
 ![tron_training](https://user-images.githubusercontent.com/62900180/188200657-c818eb82-f89d-45fa-9910-8161710b7a84.gif) |![tron_trained](https://user-images.githubusercontent.com/62900180/188200688-c156447b-643d-4202-84d2-1914587749b2.gif)


Run 'trongame.py' if you want to play against the trained AI or your friend. 

## Main files
- trongameai.py : to train our AIs using deep Q learning 
- trongame.py : if 'solo' = False, you can play against your friend. If 'solo' = True, you'll play against the AI. 
- test : bunch of files where I tried a lot of different techniques, reward strategy, game states, networks architectures etc


## Installation : 
- python 3.9.12
