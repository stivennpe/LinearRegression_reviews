# Linear Regression model for predicting document evaluation
Linear regression is a linear approximation of a causal relationship between two or more variables.
Dataset not included due to confidentiality concerns. The dataset is json formatted. The dataset includes several papers, for each of them the reviewers give an evaluation expressed in an integer,  language, remarks, and a text field, among others
Linear Regression model for predicting the evaluation score (integer) of a paper given the review (textual data).


File Linear Regression.ipynb is the collab version of the python file linear_regression.py which includes resutls and visualization of the simple implementation of the linear regression model. For comments on each part please see the .py file.
Results show 0.99 coefficient of determination (𝑅²) score and 1.83 mean squared error.

Example (Spanish):
-----
Review:

``"Este articulo presenta nuevos metodos para la creación y manejo de un software que ayude a prevenir errores en los softwares. La bibliografia muestra un gran nivel de comprención y además expresa con lenguaje adecuado su implementación. Se ha hecho una encuesta que evalua la efectividad al usar la maquinaria. La originalidad del trabajo es increible, presenta nuevas tecnicas que serán de gran ayuda al público"``

Labels range is ['1', '2', '-2', '-1', '0'].

Prediction: 
``0.085``

