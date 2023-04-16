# Markov Decision Processes

A comparative analysis of three algorithms is performed on two Markov Decision Processes (MDP). The algorithms include Value Iteration, Policy Iteration, and Q Learning. The MDPs used in this analysis are Frozen Lake and Taxi; these algorithms have been chosen to each showcase the differences of the three algorithms. Experiments were implemented using the Python libraries [OpenAI Gym](https://www.gymlibrary.dev/) and [bettermdptools](https://github.com/jlm429/bettermdptools). Additionally, custom environments were implemented to allow expirimentation with larger space sizes of 16x16 for Frozen Lake and 10x10 for Taxi.

## Running the Code

The code used to run experiments for this project can be found in this [Jupyter Notebook hosted on Google Colab](https://colab.research.google.com/github/kittyschulz/mdp/blob/main/mdp.ipynb).

Colab allows anyone to write and execute arbitrary Python code through the browser. Colab can be accessed from a desktop or mobile device. Google Colab was chosen to host the notebook so that it is hopefully more accessible to all parties. Note that you must be logged into a Google account to run code. You do not need to be logged in to view the notebook, including the outputs for each cell.

The outputs for each of the code cells should be displayed when the Colab is launched. If just reviewing the notebook, there is no need to connect to a runtime or run any cells. If you would like to explore the notebook further, you will first need to clone the repository that contains custom environments for the Taxi problem and a modified version of bettermdptools by running the first two cells of the Notebook.

Alternatively, the code can be accessed by cloning this repository and opening the notebook [mdp.ipynb](https://github.com/kittyschulz/mdp/blob/main/mdp.ipynb).
