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
![image](https://user-images.githubusercontent.com/110155589/184646298-8bff9260-288d-4276-90b5-d3638b3552d3.png)

![image](https://user-images.githubusercontent.com/110155589/184647335-b3640250-c33d-4b1a-8277-6d38354c41fd.png)
![image](https://user-images.githubusercontent.com/110155589/184647355-a6126633-c7fd-483d-9013-cfb43a460162.png)
![image](https://user-images.githubusercontent.com/110155589/184647381-b3c4dc4e-e148-4c2f-a99e-e5bfbe660871.png)


### Torodial helix
![image](https://user-images.githubusercontent.com/110155589/184646400-ac14a673-dbc2-4b26-9499-91d350726d03.png)

![image](https://user-images.githubusercontent.com/110155589/184647406-e9df4c1a-3539-4e29-8eec-9df6cf0a8964.png)
![image](https://user-images.githubusercontent.com/110155589/184647517-00fc9829-69ab-4363-8a01-8d6c99802004.png)
![image](https://user-images.githubusercontent.com/110155589/184647454-ac509415-a381-489c-8147-951c0319e352.png)
