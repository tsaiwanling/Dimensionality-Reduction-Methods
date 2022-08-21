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
![image](https://user-images.githubusercontent.com/110155589/184627853-999de168-182b-49ae-bf69-5ecb87947616.png)\
Hence there are two goals that need to be met at the same time after projection.
1. To maximize the between-classes scatter.
2. To minimize the within-classes scatter.

## Method 3 - MultiDimensional Scaling(MDS)
Another method called MDS which is to find the dataset that has the same distance matrix(DM) as the original dataset in the lower dimension.\
Using the theorem as follow\
$$Y^TY=-\frac{1}{2}HDH$$\
, this theorem gives the way to find out the data in lower dimensional space.\
Moreover, MDS doing the almost same work as PCA, they both have the same result.
## Demonstration
### Swiss roll
![image](https://user-images.githubusercontent.com/110155589/184646298-8bff9260-288d-4276-90b5-d3638b3552d3.png)

![image](https://user-images.githubusercontent.com/110155589/184648248-4e6e4c2a-8828-4c01-b75f-3ec317ac4c31.png)
![image](https://user-images.githubusercontent.com/110155589/184648301-73e3a7b8-fcb3-437a-9c55-6f5ae6876f06.png)
![image](https://user-images.githubusercontent.com/110155589/184648333-a7710301-4df7-4d19-8f29-b9e28048b882.png)


### Torodial helix
![image](https://user-images.githubusercontent.com/110155589/184646400-ac14a673-dbc2-4b26-9499-91d350726d03.png)

![image](https://user-images.githubusercontent.com/110155589/184648372-9b196f28-282a-4a36-989d-704f005b7e99.png)
![image](https://user-images.githubusercontent.com/110155589/184648419-694be8fa-3aa6-48e6-aaff-e4db5513c2db.png)
![image](https://user-images.githubusercontent.com/110155589/184648443-e3607740-943a-4f6f-8162-6dc841b72107.png)
