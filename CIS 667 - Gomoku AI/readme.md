CIS667 – GOMOKU AI

	gomoku.py– Classes for Gomoku domain for running games
	compete.py– Python script for competing two policies against each other
	performance.py – Python script for evaluating performance of policy in 30 games 
	run_games.sh – Bash script for running games and saving the output to create dataset
	dataset – this folder contains all the traning data created using the bash script 
	GomokuCNNmodel.ipynb – Python notebook for training CNN for games
	gomoku_cnn_model_state.pth – Serialized model saved as a pickle file
	report.pdf – Final report
	policies – This folder contains all the policies that can be used to play the game
		human.py – play game as a human
		minmax.py – minmax algorithm for gomoku
		model.py – class for our CNN model
		submission.py – Our Gomoku AI uses model.py to set up the neural network
		random2.py – Algorithm for making random moves on the Gomoku board 

