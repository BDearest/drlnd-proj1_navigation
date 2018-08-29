{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Learning Algorithm**\n",
    "\n",
    "\n",
    "The learning algorithm implemented here is Deep Q Learning with a 2-Layer, 128 node, fully-connected neural network using a mean-squared error loss function. A replay buffer is also used to take advantage of previous experience. After some experimentation with various learning rates, the best results were achieved with a learning rate of .0003. The replay buffer was set at 100000, the batch size at 64, gamma at .99, TAU at .001, with the network updated every 4 steps. Epsilon decay is set to .995 with a minimum of 0.1 and starting at 1.0. \n",
    "\n",
    "These settings resulted in the agent converging after 412 episodes. The graph of score over episodes is below.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "<img src=\"dqn_results.png\">"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "During the course of experimentation, made the following changes to try to get better results. The experiments that converged can be found in the OtherCheckpoints directory: Learning rate changes-Tried .0002, .0003, .0004 and .0005 Neural Net Changes-Experimented with 3 Layer instead of 2 Layer (model in folder) Batch Size-Tried 128 and 32 in addition to 64. Agent seed-Tried 0 for agent's seed Loss functions-Poisson NLL Loss and Cross Entropy"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "**Ideas for Future Work**\n",
    "\n",
    "This could possibly be improved by implementing either the double deep q learning algorithm or prioritized experience replay or a combination of both. \n",
    "\n",
    "\n"
   ]
  },
  {
   "cell_type": "raw",
   "metadata": {},
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.6.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
