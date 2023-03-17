# IR-Crack-detection
Crack Detection Based on Infrared thermography (IRT) - PyTorch

## 1. Paper

## 2. Dataset

The link of the dataset: Googl Drive; Baidu Yun

(1) This dataset is used for crack detection based on the three types of images: the visible image, infrared image, and fusion image.

(2) The dataset also considers different conditions and periods, including single and multi cracks, thin and thick cracks, clean and rough backgrounds, light and dark backgrounds, and three periods in one day.

(3) Three periods were used to acquire data (images), including the morning (8:00 am), noon (12:00 pm), and dusk (5:00 pm)

| Dataset | Number of Images | Crack Pixel(%) | Non-Crack Pixel (%)|
|---|---|---|---|
| Morning | 186 | 3.85 | 96.15 |
| Noon | 142 | 3.97 | 96.03 |
| Dusk | 120 | 3.20 | 96.80 |
| Train | 382 | 3.86 | 96.14 |
| Test | 66 | 2.88 | 97.12 |
| Total | 448 | 3.71 | 96.29 |


Example images: 
(a) Single crack, (b) multi cracks, (c) thin crack, (d) thick crack, (e) clean background, (f) rough background, (g) light background, and (h) dark background.

<img width="651.2" height="991.2" src="https://user-images.githubusercontent.com/62622741/150647460-712ed41b-8193-46b9-8fe3-a332facf8541.jpg"/>


## References
If you take use of our datasets, please cite our papers:
@article{liu2022asphalt,
  title={Asphalt pavement crack detection based on convolutional neural network and infrared thermography},
  author={Liu, Fangyu and Liu, Jian and Wang, Linbing},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  volume={23},
  number={11},
  pages={22145--22155},
  year={2022},
  publisher={IEEE}
}


