# Image_Singular_Value_Decomposition
This program uses the singular value decompsition on a grayscaled image and reconstructs it using the first "k" singular values

## SVD Image Compression Results

### Compressed Images (using top-k singular values):

| k = 5 | k = 10 | k = 15 | k = 20 |
|-------|--------|--------|--------|
| ![A_5](A_5.png) | ![A_10](A_10.png) | ![A_15](A_15.png) | ![A_20](A_20.png) |

| k = 50 | k = 100 | k = 200 | k = 300 |
|--------|---------|---------|---------|
| ![A_50](A_50.png) | ![A_100](A_100.png) | ![A_200](A_200.png) | ![A_300](A_300.png) |

| k = 500 |
|---------|
| ![A_500](A_500.png) |

---

### Error Images (difference between original and compressed):

| k = 5 | k = 10 | k = 15 | k = 20 |
|-------|--------|--------|--------|
| ![Error_5](Error_5.png) | ![Error_10](Error_10.png) | ![Error_15](Error_15.png) | ![Error_20](Error_20.png) |

| k = 50 | k = 100 | k = 200 | k = 300 |
|--------|---------|---------|---------|
| ![Error_50](Error_50.png) | ![Error_100](Error_100.png) | ![Error_200](Error_200.png) | ![Error_300](Error_300.png) |

| k = 500 |
|---------|
| ![Error_500](Error_500.png) |
