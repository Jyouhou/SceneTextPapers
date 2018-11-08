# SceneTextPapers
Tracking the latest progress in Scene Text Detection and Recognition: must-read papers well organized

## Information about this repository
This repo serves as a complement to our working paper:

- __Scene Text Detection and Recognition: The Deep Learning Era__. _Shangbang Long, Xin He, Cong Yao_. [Link(to be available in a few days)]()

__This repository will be updated in the following days, together with our paper.__

## Papers

### Before: Deep Learning Papers  You Must Know

### Main: Scene Text Detection and Recognition

#### Detection

##### Pipeline Simplification

###### Anchor-based methods

###### Region proposal methods

##### Differnt Prediction Units

###### Text instance level

###### Sub-component

##### Specific Targets

###### Long text

###### Multi-oriented text

###### Irregular text

###### Speed up

###### Easy instance segmentation

###### Retrieving designated text

###### Against Complex Background

#### Recognition

##### CTC based methods

##### Attention based methods

#### End-to-End Text Spotting

#### Auxilliary Techs

##### Synthetic Data

##### Bootstrapping

##### Deblurring

##### Context Information

##### Adversarial Attack

### Datasets

| Dataset (Year) | Image Num (train/test) | Text Num (train/test) | Orientation| Language| Characteristics |
|:------:|:------:|:------:|:------:|:------:|:------:|
| [ICDAR03 (2003)](http://www.iapr-tc11.org/mediawiki/index.php?title=ICDAR_2003_Robust_Reading_Competitions) | 509 (258/251) | 2276 (1110/1156) | Horizontal | En | - |
| [Char74k (2009)](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/) | 74107 (-/-) | 74107 (-/-) | Horizontal| En, Kanada | Character label |
| [SVT (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=The_Street_View_Text_Dataset) | 350 (100/250) | 904 (257/647) | Horizontal| En| - |
| [KAIST (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=KAIST_Scene_Text_Database) | 3000 (-/-) | 5000 (-/-) | Horizontal| En, Ko| Distorted |
| [SVHN (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=The_Street_View_House_Numbers_(SVHN)_Dataset) | - (-/-) | 600000 (-/-) | Horizontal| -| House number digits |
| [NEOCR (2011)](http://www.iapr-tc11.org/mediawiki/index.php?title=NEOCR:_Natural_Environment_OCR_Dataset) | 659 (-/-) | 5238 (-/-) | Multi-oriented| 8 langs| - |
| [OSTD (2011)](http://media-lab.ccny.cuny.edu/wordpress/cyi/www/project_scenetextdetection.html) | 89 (-/-) | 218 (-/-) | Multi-oriented| En| - |
| [IIIT 5K-Word (2012)](http://cvit.iiit.ac.in/projects/SceneTextUnderstanding/IIIT5K.html) | 5000 (-/-) | 5000 (2000/3000) | Horizontal| -| cropped |
| [ICDAR13 Scene Text(2013)](http://dagdata.cvc.uab.es/icdar2013competition/) | 462 (229/233) | - (848/1095) | Horizontal | En | - |
| [MSRA-TD500 (2012)](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_(MSRA-TD500)) | 500 (300/200) | 1719 (1068/651) |  Multi-Oriented | En, Ch |  Long text |
| [HUST-TR400 (2014)](http://mclab.eic.hust.edu.cn/UpLoadFiles/dataset/HUST-TR400.zip) | 400 (400/-) | - (-/-) |  Multi-Oriented | En, Ch |  Long text |
| [ICDAR15 Incidental Text(2015)](http://rrc.cvc.uab.es/?ch=4&com=introduction) | 1500 (1000/500) | - (-/-) | Multi-Oriented | En |  Blur/Small/Defocused |
| [ICDAR17/RCTW(2017)](http://u-pat.org/ICDAR2017/program_competitions.php) | 12263 (8034/4229) | - (-/-) | Multi-Oriented | Chinese | - |
| [ICDAR17/RRC-MLT(2017)](http://rrc.cvc.uab.es/?ch=8) | 18000 (9000/9000) | - (-/-) | Multi-Oriented |  9 langs | - |
| [Total-Text (2017)](https://github.com/cs-chan/Total-Text-Dataset) | 1555 (1255/300) | - (-/-) | Multi-Oriented,  Curved | En, Ch | Irregular/polygon label |
| [CTW (2017)](https://ctwdataset.github.io) |  32K ( 25K/6K) |  1M ( 812K/205K) | Multi-Oriented | Chinese |  Fine-grained annotation |
| [CTW1500 (2017)](https://github.com/Yuliang-Liu/Curve-Text-Detector) | 1500 (1000/500) | - (-/-) | Multi-Oriented,  Curved | En | Bounding box with $14$ vertexes |

