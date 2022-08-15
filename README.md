# Dimensionality-Reduction-Methods
Nowadays, most of data are in high-dimensional space to save the large amount of information, but it would not be observed or analyzed intuitively. Hence, there are three linear methods provide different concepts to preserve the characteristics of data as much as possible and make it visualized in lower-dimensional space.
## Method 1 - Principal Component Analysis(PCA)
The concept of PCA is to make the projected data as dispersed as possible, as shown in the figure below, red points are the original data points, blue line is the projection by PCA and the green stars on the PCA line are the projected data.\
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
![image](https://user-images.githubusercontent.com/110155589/184636816-0b032987-70e0-45c2-9b5e-f370db2edd53.png)![image](https://user-images.githubusercontent.com/110155589/184636825-eb38c54e-7c02-4557-9203-ae6070785fe4.png)
![image](https://user-images.githubusercontent.com/110155589/184636843-23f81d9f-f4c9-4f24-a36d-0c88998756ba.png)


### Torodial helix
![image](https://user-images.githubusercontent.com/110155589/184642838-cd2e6d15-57de-4585-9f11-7cd46b733c3d.png)
![image](https://user-images.githubusercontent.com/110155589/184642851-09a0a693-4a82-4e56-88d4-e8f563a8ec4c.png)
![image](https://user-images.githubusercontent.com/110155589/184642867-7026ab44-eda2-434f-9fb3-bdb21a12d45f.png)
