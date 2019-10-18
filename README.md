# Recommendations with IBM

In this project a recommendation engine is built using data which captures how users interact with
articles on the IBM Watson Studio platform. The Studio platform is an online community of data science
professionals, where members post articles, notebooks and tutorials. The dataset used in the project
contains information for 45,993 user-article interactions, obtained in collaboration with IBM. 
The recommedation engine gives article suggestion based on, simple ranking of articles based on the size 
of their user interactions, user-user collaborative filtering, and matrix factorization. 
 

## Files in the project besides the README:

1. data/articles_community.csv: contains the content information for each article, such as the article id,
								description, and body.
2. data/user-item-interactions.csv: The csv file showing the user-article interactions.
3. Recommendations_with_IBM.ipynb: The Jupyter notebook file showing the project implementation.
4. project_tests.py: contains the codes used in running project test. 
5. top_5.p, top_10.p, and top_20.p: are files needed to successfully run project_tests.py
6. user_item_matrix.p: The default user-item matrix used in matrix factorization predictions.
7. requirements.txt: The file containing the list of libraries required to run project.

### Instructions:
1. To run Recommendations_with_IBM.ipynb, create a python virtual environment with conda and run 
   the following from the project's home directory:
	- pip install -r requirements.txt
	- jupiter notebook
