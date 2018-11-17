# Reinforcement learning + transfer learning for Mountaincar and Centipede

dqn_mountaincar.ipynb: Deep Q network with 2 FC layers. Completed in 58 trials. Fine-tuned learning rate, memory size, batch size, dense layer, etc

dqn_atari.ipynb: Deep Q network with 2 CNN layers. Achieved high score of 21k within 32 episodes. Adapted previous code in dqn_mountaincar.ipynb to have CNN and some image pre-processing using opencv package.

transfer_learning.ipynb: Further adapted previous code in dqn_atari.ipynb for transfer learning. Trained a dqn_centipede model for around 60 episode and then froze the first layer in new model for dqn_spaceinvaders. Performance is the same as training a dqn_spaceinvaders model from scratch. Perhaps I need to train the initial model way longer and also consider a deeper CNN so that I have more layers to play around.
