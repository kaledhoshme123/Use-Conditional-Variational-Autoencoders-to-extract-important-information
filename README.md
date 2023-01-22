# Use Conditional Variational Autoencoders to extract important information
The study relied on conditional Variational Autoencoders to generate x-ray images, so that we can be able to regenerate the images according to the most important information that the x-ray images can contain (important information extraction).

The study presented the methodology by suggesting the structure of the encoder and the structure of the decoder in addition to the use of conditional generation, to make the latent space more regular.
# Results:
## Conditional Variational Autoencoders Results:

| #1    | #2    |
| :---: | :---: |
| ![download - 2023-01-23T000432 299](https://user-images.githubusercontent.com/108609519/213942780-4cd26026-bca7-482f-90df-f6de67073250.png)   | ![image](https://user-images.githubusercontent.com/108609519/213942815-bea053be-b3fa-4210-b837-94162fee0663.png)   |

### Samples of chest x-ray images from the test data:

![download - 2023-01-23T000758 571](https://user-images.githubusercontent.com/108609519/213942910-d559a11c-3f39-44e3-883f-80bb67f51c2e.png)

### Samples of chest X-ray images from test data after regeneration using (CVAE):

![download - 2023-01-23T000831 622](https://user-images.githubusercontent.com/108609519/213942934-ea1d6563-fa13-4bd2-a93e-54acf44f3c99.png)

## Classification Section:
In this part, it was tested that the generated x-ray images contain the most important information, by building a neural network to identify pulmonary diseases, and the images generated from the obstetric network were tested, by reaching a balanced model and high accuracy during Training and testing process.
### Results:

| #1 | #2    | #3    |
| :---:   | :---: | :---: |
| ![image](https://user-images.githubusercontent.com/108609519/213943055-3d37ed23-ce7a-4a7c-b386-9c253b727c26.png) | ![download - 2023-01-23T001234 541](https://user-images.githubusercontent.com/108609519/213943074-9b310c28-8b8f-4eb7-ac9d-eae75069c2c0.png)   | ![download - 2023-01-23T001259 574](https://user-images.githubusercontent.com/108609519/213943086-1617de22-e667-4377-b4de-0ce1aa8b6fe9.png)   |

| #confusion matrix | #classification report    |
| :---:   | :---: |
| ![image](https://user-images.githubusercontent.com/108609519/213943141-15aafc20-94b6-484a-b278-4383d7fba820.png) | ![image](https://user-images.githubusercontent.com/108609519/213943207-4990e9d2-d18d-42d9-91dc-7379743eee35.png)   |


