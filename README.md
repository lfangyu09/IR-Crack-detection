# IR-Crack-detection
Crack Detection Based on Infrared thermography (IRT) - PyTorch

## 1. Dataset for multi crack-detection tasks

Infrared thermography and deep learning for multi crack-detection tasks (multiple-type distress detection, crack severity classification, and crack segmentation).

(1) Multiple-type distress detection

Multiple-type distress detection in asphalt concrete pavement using infrared thermography and deep learning

Paper: https://doi.org/10.1016/j.autcon.2024.105355 

Dataset: https://doi.org/10.5281/zenodo.11638443 

(2) Crack severity classification

Deep learning and infrared thermography for asphalt pavement crack severity classification

Paper: https://doi.org/10.1016/j.autcon.2022.104383 

Dataset: https://doi.org/10.5281/zenodo.11625820 

Asphalt pavement fatigue crack severity classification by infrared thermography and deep learning

Paper: https://doi.org/10.1016/j.autcon.2022.104575 

Dataset: https://doi.org/10.5281/zenodo.11625865 

(3) Crack segmentation

Asphalt pavement crack detection based on convolutional neural network and infrared thermography

Paper: https://doi.org/10.1109/TITS.2022.3142393 

Dataset: https://doi.org/10.5281/zenodo.11624965

## 2. Dataset (for crack segmentation)

The link of the dataset: [Googl Drive](https://drive.google.com/drive/folders/1r8jHJYm63awg21wTYRYMb6z_Xu1keoHq?usp=sharing); [Zenodo](https://doi.org/10.5281/zenodo.11624965);

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
If you take use of our datasets, please cite our papers (https://ieeexplore.ieee.org/abstract/document/9686599):

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


