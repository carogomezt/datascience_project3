# Recommendations with IBM Project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation<a name="installation"></a>
1. Clone the repository.
2. Create a conda environment.
```
$ conda create --name <env> --file requirements.txt 
```
3. Run the notebook.
```
$ jupyter notebook  
```
## Project Motivation <a name="motivation"></a>
For this project was analyzed the interactions that users have with articles on the IBM Watson Studio platform,
and was made recommendations to them about new articles that they would like.
The analysis was made following the steps described on the notebook: Exploratory Data Analysis, Rank Based Recommendations,
User-User Based Collaborative Filtering and Matrix Factorization.

## File Descriptions<a name="files"></a>

1. **data**: Folder with .csv files with users and articles data.
2. **project_tests**: File with test.
3. **README.md**: File with repository information.
4. **Recommendations_with_IBM.html**: File with the analysis of the project in .html format.
5. **Recommendations_with_IBM.ipynb**: File with the analysis of the project in .ipynb format.
6. **requirements.txt**: File with requirements of the project.
7. **top_5.p**: File used in the tests.
8. **top_10.p**: File used in the tests.
9. **top_20.p**: File used in the tests.
10. **user_item_matrix.p**: File used to load the user_item_matrix in the analysis.


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The Datasets used on this project are being provided by IBM Watson Studio platform.