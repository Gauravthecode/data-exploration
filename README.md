# data-exploration
exploring data

# Ridge expression
from sklearn.model_selection import cross_val_score
from sklearn.linear_model import LinearRegression,Ridge,Lasso
df = Ridge(alpha = 1.0)
# fitting the model
scores = cross_val_score(df, x, y, cv = 5)
print("Scores : ",scores)

i am inside the master branch

