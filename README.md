# Sign Language Digits Recognition with MobileNet

This is an simple implementation of MobileNet for sign language digit recognition.

## Dataset

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset) or [Github](https://github.com/ardamavi/Sign-Language-Digits-Dataset).

This data set contains images of sign language digits. There are ten classes, labeled as 0 through 9, and each class is made up of images of hands showing the sign for that particular digit. Each class has between 204 and 208 samples. The total data set contains 2062 samples.

| <img src="examples/example_0.JPG"> | <img src="examples/example_1.JPG"> | <img src="examples/example_2.JPG"> | <img src="examples/example_3.JPG"> | <img src="examples/example_4.JPG"> |
| :--------------------------------: | :--------------------------------: | :--------------------------------: | :--------------------------------: | :--------------------------------: |
|                 0                  |                 1                  |                 2                  |                 3                  |                 4                  |
| <img src="examples/example_5.JPG"> | <img src="examples/example_6.JPG"> | <img src="examples/example_7.JPG"> | <img src="examples/example_8.JPG"> | <img src="examples/example_9.JPG"> |
|                 5                  |                 6                  |                 7                  |                 8                  |                 9                  |

### Details of datasets:

- Image size: 100 x 100 pixels
- Color space: RGB
- Number of classes: 10 (Digits: 0-9)
- Number of participant students: 218
- Number of samples per student: 10
