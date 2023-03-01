Here is where you include:
  - Background on your code files
  - How to run your code, guide to install any additional packages
  - Results, interpretation and reflection

Project Readme Report

Ayah Metwali

 - Background on your code files:
	It is based on a Kaggle competition about predicting the survival rate of people on the Titanic

 - How to run your code, guide to install any additional packages:
	Packages required have been the ones used in class, except for one. The marker would have to install
	XGBoost to be able to run the XGBClassifier.

	Open file using Jupyter Notebook and then run all the cells from top to bottom.
	At the very end of the Notebook there will be a file named "submissions" beign created on the last cell.


 - Results, interpretation and reflection:
	Results:
		Proof of submission of the code is labeled as KaggleSubmissionAndScore.PNG in github repository
	
		The score received from the competition was 0.76315.

	Interpretation:
		I have used LogisticRegression, RandomForest, GradientBoosting, SVC, and XGBClassifier for comparing the initial sets
		of results using cross validation.
		Their hyperparameters were tuned for being able to use grid search.
		From this, it was found that the best model was XGBClassifier.

	Reflection:
		XGBoost was included because of the example prompt the professor gave us had it, so I thought it sounded interesting and added it to 
		my project.

		It was crazy to see that XGBClassifier was better than RandomForest by 0.001 difference.
		
		I came into this program wanting to explore knowledge on machine learning and actually try to do something
		on my own without just a structured format. So this project helped me further understand what I want to do for
		our capstone next semester.

		From what I looked up because I was curious as to why it's only a small margin is a few reasons:
			- XGBoost is good for unbalanced datasets and prunes the tree right away before doing the "actual" modeling
			- Another reason was using the hyperparameters won't cause a drastic change in the tree because its only applied to one part of the tree at the beginning

		However with RandomForest:
			- It will not overfit if it was properly pre-processed and cleaned
			- It is also much easier to tune.
	
	