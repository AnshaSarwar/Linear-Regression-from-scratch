📈 **Linear Regression from Scratch**

It is a fundamental machine learning project where the algorithm is implemented without relying on external libraries. 

This Regression class is a basic implementation of linear regression, designed to predict a target variable based on input features. The class includes methods to train the model (fit) and make predictions (predict).

**Initialization:** The __init__ method sets the learning rate (lr) and the number of iterations (n_iters). It also initializes the weights and bias to None.

**Fit Method**: The fit method is used to train the model. It initializes the weights as a zero vector and the bias as zero. The method iteratively updates the weights and bias using gradient descent. During each iteration, it calculates the predicted values (y_pred) and computes the gradients (dw for weights and db for bias). These gradients are then scaled by the learning rate and used to adjust the weights and bias. The method also includes a convergence check using a tolerance level to stop training early if the improvement in loss falls below a certain threshold.

**Predict Method**: The predict method generates predictions by applying the linear equation **y=w⋅x+b**, where **w** represents the weights and **b** represents the bias.

**Model Training**: The fit method updates the weights and bias over a specified number of iterations, or until the loss converges, helping the model learn the relationship between the input features (X) and the target variable (y).

This code demonstrates the essential components of linear regression, such as gradient descent, loss calculation, and model convergence.
