# Personal_Movie_Recommendation_System
We use EM (expectation maximization) algorithm to develop a personal movie recommendation system based on the movie choice of CSE 250A students, Fall 2022, UCSD. Project completed as part of homework 6 of CSE 250A of UCSD, CSE, Fall 2022.

# Tasks:
For a detailed description of the task please consult the file 'Problem Statement and sample sol.pdf'. First, we do a sanity check by printing the most popular movie names. Then, we obtain a Bayesian model for this movie rating system and derive the EM update rule (the derivation can be found in 'Problem Statement and sample sol.pdf'). Then we implement the EM algorithm's iterations, keeping in check the increment of log-likelihoods with iterations. Finally, we get a personal movie recommendation system, where upon entering a student's ID (or the index of it) in the code, we will be able to see a list of unseen movies by the student sorted by his/her expected ratings. In this current code, we show this list for a random student.  

# Files :
1.  hw8 movies.txt: List of names of the movies. 
2.  hw8 ids.txt: List of all student IDs who submitted their movie choices. 
3.  hw8 ratings.txt: Binary recommendations for each student id in favor or against the movie names. 0 for not recommended and 1 for recommended. 
4.  Problem Statement and sample sol.pdf: Detailed problem statement, derivations, and a sample solution with code outputs are given.
5.  hw8_probR_init.txt, hw8_probZ_init.txt: Initialization files for probabilities as mentioned in part (e) of the file 'Problem Statement and sample sol.pdf'.
6.  code.ipynb : Code for each task as mentioned in 'Problem Statement and sample sol.pdf'.



# Execution :
Execute code.ipynb notebook sequentially to perform all the tasks one by one, in the order mentioned in 'Problem Statement and sample sol.pdf'.
