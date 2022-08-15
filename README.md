# Dimensionality-Reduction-Methods
Nowadays, most of data are in high-dimensional space to save the large amount of information, but it would not be observed or analyzed intuitively. Hence, there are three linear methods provide different concepts to preserve the characteristics of data as much as possible and make it visualized in lower-dimensional space.
## Method 1 - Principal Component Analysis(PCA)
The concept of PCA is to make the projected data as dispersed as possible, as shown in the figure below, red points are the original data points, blue line is the projection by PCA and the green stars on the PCA line are the projected data.
![image](https://user-images.githubusercontent.com/110155589/184601889-ebc9abe1-a24f-4000-ba2f-c8e38ff22e32.png)\
Hence we can conclude two equivalent purpose:
1. To maximize the variance of the projected data in lower-dimensional space.
2. To minimize the sum of square distances between original data and projected data

## Method 2 - Fisher Discriminant Analysis(FDA)
LDA is a method similar to PCA. The concept of the LDA is to make the projected data as dispersed as possible, while keeping the same group of data as close together as possible. As shown in the figure below.\
![image](https://user-images.githubusercontent.com/110155589/184627853-999de168-182b-49ae-bf69-5ecb87947616.png)

## Method 3 - MultiDimensional Scaling(MDS)
Another method called MDS which is to find the dataset that has the same distance matrix(DM) as the original dataset in the lower dimension.

## Demonstration
### Swiss roll
![image](https://user-images.githubusercontent.com/110155589/184628255-7c91b173-b35e-4972-83ab-dd58c6b122ef.png)![image](https://user-images.githubusercontent.com/110155589/184628320-705b2d94-7d76-4a31-b161-965b2ef76d34.png)


### Torodial helix
