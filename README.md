# PCA

## Calculating Principle Components without using  sklearn.decomposition 

### Calculation Steps

##### a. First make the data zero centered by subtracting mean of each column from the column itself


##### b. Find the covariance matrix of the data using the following formula


##### c. Find the eigenvalues of the covariance matrix and their corresponding eigenvectors in ordered manner, do not forget the sort the eigenvalues in descending order. You can use np.linalg.eig() function to find eigenvalues and eigenvectors


##### d. Lastly use the first k columns of the eigenmatrix to make the transformation

![alt text](https://github.com/yctasoglu/PCA/blob/main/SnapShots/38C69E83-6FD1-475B-BA57-DA773F306CC6.png)
![alt text](https://github.com/yctasoglu/PCA/blob/main/SnapShots/615829C7-872F-4B2B-B113-5B76843D6910.png)

