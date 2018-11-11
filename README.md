# SceneTextPapers
Tracking the latest progress in Scene Text Detection and Recognition: must-read papers well organized

## Information about this repository
This repo serves as a complement to our working paper:

- __Scene Text Detection and Recognition: The Deep Learning Era__. _Shangbang Long, Xin He, Cong Yao_. [Link(to be available in a few days)]()

__This repository will be updated in the following days, together with our survey paper.__

## Papers

### I. Other Survey Papers:
1. __Text localization and recognition in images and video.__ _Uchida, Seiichi_. 2014 [paper](https://link.springer.com/referenceworkentry/10.1007%2F978-0-85729-859-1_28)
2. __Text detection and recognition in imagery: A survey.__ _Ye, Qixiang and Doermann, David_. 2015 [paper](https://ieeexplore.ieee.org/abstract/document/6945320/)
3. __Text detection, tracking and recognition in video: A comprehensive survey.__ _Yin, Xu-Cheng and Zuo, Ze-Yu and Tian, Shu and Liu, Cheng-Lin_. 2016 [paper](https://ieeexplore.ieee.org/abstract/document/7452620/)
4. __Scene text detection and recognition: Recent advances and future trends.__ _Zhu, Yingying and Yao, Cong and Bai, Xiang_. 2016 [paper](https://link.springer.com/article/10.1007/s11704-015-4488-0)


### II. Main: Scene Text Detection and Recognition

#### 2.1 Detection

##### 2.1.1 Pipeline Simplification

###### Anchor-based methods
1. __Single Shot Text Detector With Regional Attention.__ _He, Pan and Huang, Weilin and He, Tong and Zhu, Qile and Qiao, Yu and Li, Xiaolin_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Single_Shot_Text_ICCV_2017_paper.pdf)
2. __TextBoxes: A Fast Text Detector with a Single Deep Neural Network.__ _Liao, Minghui and Shi, Baoguang and Bai, Xiang and Wang, Xinggang and Liu, Wenyu_. 2017 [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14202/14295)
3. __Deep Matching Prior Network: Toward Tighter Multi-oriented Text Detection.__ _Liu, Yuliang and Jin, Lianwen_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Deep_Matching_Prior_CVPR_2017_paper.pdf)
4. __Detecting Oriented Text in Natural Images by Linking Segments.__ _Shi, Baoguang and Bai, Xiang and Belongie, Serge_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shi_Detecting_Oriented_Text_CVPR_2017_paper.pdf)
5. __EAST: An Efficient and Accurate Scene Text Detector.__ _Zhou, Xinyu and Yao, Cong and Wen, He and Wang, Yuzhi and Zhou, Shuchang and He, Weiran and Liang, Jiajun_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_EAST_An_Efficient_CVPR_2017_paper.pdf)

###### Region proposal methods
1. __Detecting Curve Text in the Wild: New Dataset and New Solution.__ _Yuliang, Liu and Lianwen, Jin and Shuaitao, Zhang and Sheng, Zhang_. 2017 [paper](https://arxiv.org/abs/1712.02170)
2. __R2CNN: rotational region CNN for orientation robust scene text detection.__ _Jiang, Yingying and Zhu, Xiangyu and Wang, Xiaobing and Yang, Shuli and Li, Wei and Wang, Hua and Fu, Pei and Luo, Zhenbo_. 2017 [paper](https://arxiv.org/abs/1706.09579)
3. __Arbitrary-Oriented Scene Text Detection via Rotation Proposals.__ _Ma, Jianqi and Shao, Weiyuan and Ye, Hao and Wang, Li and Wang, Hong and Zheng, Yingbin and Xue, Xiangyang_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8323240/)
4. __weakly supervised text attention network for generating text proposals in scene images.__ _Rong, Li and MengYi, En and JianQiang, Li and HaiBin, Zhang_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8269992/)
5. __Rotation-Sensitive Regression for Oriented Scene Text Detection.__ _Liao, Minghui and Zhu, Zhen and Shi, Baoguang and Xia, Gui-song and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liao_Rotation-Sensitive_Regression_for_CVPR_2018_paper.pdf)
6. __Feature Enhancement Network: A Refined Scene Text Detector.__ _Sheng, Zhang and Yuliang, Liu and Lianwen, Jin and Canjie, Luo_. 2017 [paper](https://arxiv.org/abs/1711.04249)

##### 2.1.2 Differnt Prediction Units

###### Text instance level
1. __Detecting Curve Text in the Wild: New Dataset and New Solution.__ _Yuliang, Liu and Lianwen, Jin and Shuaitao, Zhang and Sheng, Zhang_. 2017 [paper](https://arxiv.org/abs/1712.02170)
2. __TextBoxes: A Fast Text Detector with a Single Deep Neural Network.__ _Liao, Minghui and Shi, Baoguang and Bai, Xiang and Wang, Xinggang and Liu, Wenyu_. 2017 [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14202/14295)
3. __EAST: An Efficient and Accurate Scene Text Detector.__ _Zhou, Xinyu and Yao, Cong and Wen, He and Wang, Yuzhi and Zhou, Shuchang and He, Weiran and Liang, Jiajun_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_EAST_An_Efficient_CVPR_2017_paper.pdf)
4. __R2CNN: rotational region CNN for orientation robust scene text detection.__ _Jiang, Yingying and Zhu, Xiangyu and Wang, Xiaobing and Yang, Shuli and Li, Wei and Wang, Hua and Fu, Pei and Luo, Zhenbo_. 2017 [paper](https://arxiv.org/abs/1706.09579)
5. __Arbitrary-Oriented Scene Text Detection via Rotation Proposals.__ _Ma, Jianqi and Shao, Weiyuan and Ye, Hao and Wang, Li and Wang, Hong and Zheng, Yingbin and Xue, Xiangyang_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8323240/)
6. __Deep Matching Prior Network: Toward Tighter Multi-oriented Text Detection.__ _Liu, Yuliang and Jin, Lianwen_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Deep_Matching_Prior_CVPR_2017_paper.pdf)
7. __Deep Direct Regression for Multi-Oriented Scene Text Detection.__ _He, Wenhao and Zhang, Xu-Yao and Yin, Fei and Liu, Cheng-Lin_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Deep_Direct_Regression_ICCV_2017_paper.pdf)
8. __Fused Text Segmentation Networks for Multi-oriented Scene Text Detection.__ _Dai, Yuchen and Huang, Zheng and Gao, Yuting and Chen, Kai_. 2017 [paper](https://arxiv.org/abs/1709.03272)
9. __Feature Enhancement Network: A Refined Scene Text Detector.__ _Sheng, Zhang and Yuliang, Liu and Lianwen, Jin and Canjie, Luo_. 2017 [paper](https://arxiv.org/abs/1711.04249)
10. __Rotation-Sensitive Regression for Oriented Scene Text Detection.__ _Liao, Minghui and Zhu, Zhen and Shi, Baoguang and Xia, Gui-song and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liao_Rotation-Sensitive_Regression_for_CVPR_2018_paper.pdf)

###### Bottom-up (Pixel)
1. __Scene text detection via holistic, multi-channel prediction.__ _Yao, Cong and Bai, Xiang and Sang, Nong and Zhou, Xinyu and Zhou, Shuchang and Cao, Zhimin_. 2016 [paper](https://arxiv.org/abs/1606.09002)
2. __Multi-oriented text detection with fully convolutional networks.__ _Zhang, Zheng and Zhang, Chengquan and Shen, Wei and Yao, Cong and Liu, Wenyu and Bai, Xiang_. 2016 [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Zhang_Multi-Oriented_Text_Detection_CVPR_2016_paper.html)
3. __Self-organized Text Detection with Minimal Post-processing via Border Learning.__ _Wu, Yue and Natarajan, Prem_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wu_Self-Organized_Text_Detection_ICCV_2017_paper.pdf)
4. __Multi-scale FCN with Cascaded Instance Aware Segmentation for Arbitrary Oriented Word Spotting in the Wild.__ _He, Dafang and Yang, Xiao and Liang, Chen and Zhou, Zihan and Ororbia, Alexander G and Kifer, Daniel and Giles, C Lee_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/He_Multi-Scale_FCN_With_CVPR_2017_paper.pdf)
5. __Single Shot Text Detector With Regional Attention.__ _He, Pan and Huang, Weilin and He, Tong and Zhu, Qile and Qiao, Yu and Li, Xiaolin_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Single_Shot_Text_ICCV_2017_paper.pdf)
6. __PixelLink: Detecting Scene Text via Instance Segmentation.__ _Dan, Deng and Haifeng, Liu and  Xuelong, Li and Deng, Cai_. 2018 [paper](https://arxiv.org/abs/1801.01315)

###### Bottom-up (Components)
1. __Detecting text in natural image with connectionist text proposal network.__ _Tian, Zhi and Huang, Weilin and He, Tong and He, Pan and Qiao, Yu_. 2016 [paper](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_4)
2. __Aggregating local context for accurate scene text detection.__ _He, Dafang and Yang, Xiao and Huang, Wenyi and Zhou, Zihan and Kifer, Daniel and Giles, C Lee_. 2016 [paper](https://link.springer.com/chapter/10.1007/978-3-319-54193-8_18)
3. __Detecting Oriented Text in Natural Images by Linking Segments.__ _Shi, Baoguang and Bai, Xiang and Belongie, Serge_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shi_Detecting_Oriented_Text_CVPR_2017_paper.pdf)
4. __Scene Text Detection with Novel Superpixel Based Character Candidate Extraction.__ _Wang, Cong and Yin, Fei and Liu, Cheng-Lin_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8270087/)
5. __Deep Residual Text Detection Network for Scene Text.__ _Zhu, Xiangyu and Jiang, Yingying and Yang, Shuli and Wang, Xiaobing and Li, Wei and Fu, Pei and Wang, Hua and Luo, Zhenbo_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8270068/)
6. __Multi-Oriented Scene Text Detection via Corner Localization and Region Segmentation.__ _Lyu, Pengyuan and Yao, Cong and Wu, Wenhao and Yan, Shuicheng and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1688.pdf)

##### 2.1.3 Specific Targets

###### Long text
1. __Detecting Oriented Text in Natural Images by Linking Segments.__ _Shi, Baoguang and Bai, Xiang and Belongie, Serge_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shi_Detecting_Oriented_Text_CVPR_2017_paper.pdf)
2. __R2CNN: rotational region CNN for orientation robust scene text detection.__ _Jiang, Yingying and Zhu, Xiangyu and Wang, Xiaobing and Yang, Shuli and Li, Wei and Wang, Hua and Fu, Pei and Luo, Zhenbo_. 2017 [paper](https://arxiv.org/abs/1706.09579)
3. __Multi-Oriented Scene Text Detection via Corner Localization and Region Segmentation.__ _Lyu, Pengyuan and Yao, Cong and Wu, Wenhao and Yan, Shuicheng and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1688.pdf)

###### Multi-oriented text
1. __R2CNN: rotational region CNN for orientation robust scene text detection.__ _Jiang, Yingying and Zhu, Xiangyu and Wang, Xiaobing and Yang, Shuli and Li, Wei and Wang, Hua and Fu, Pei and Luo, Zhenbo_. 2017 [paper](https://arxiv.org/abs/1706.09579)
2. __TextBoxes: A Fast Text Detector with a Single Deep Neural Network.__ _Liao, Minghui and Shi, Baoguang and Bai, Xiang and Wang, Xinggang and Liu, Wenyu_. 2017 [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14202/14295)
3. __Deep Matching Prior Network: Toward Tighter Multi-oriented Text Detection.__ _Liu, Yuliang and Jin, Lianwen_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Liu_Deep_Matching_Prior_CVPR_2017_paper.pdf)
4. __Arbitrary-Oriented Scene Text Detection via Rotation Proposals.__ _Ma, Jianqi and Shao, Weiyuan and Ye, Hao and Wang, Li and Wang, Hong and Zheng, Yingbin and Xue, Xiangyang_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8323240/)
5. __Detecting Oriented Text in Natural Images by Linking Segments.__ _Shi, Baoguang and Bai, Xiang and Belongie, Serge_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Shi_Detecting_Oriented_Text_CVPR_2017_paper.pdf)
6. __EAST: An Efficient and Accurate Scene Text Detector.__ _Zhou, Xinyu and Yao, Cong and Wen, He and Wang, Yuzhi and Zhou, Shuchang and He, Weiran and Liang, Jiajun_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_EAST_An_Efficient_CVPR_2017_paper.pdf)
7. __Rotation-Sensitive Regression for Oriented Scene Text Detection.__ _Liao, Minghui and Zhu, Zhen and Shi, Baoguang and Xia, Gui-song and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liao_Rotation-Sensitive_Regression_for_CVPR_2018_paper.pdf)
8. __Geometry-Aware Scene Text Detection With Instance Transformation Network.__ _Wang, Fangfang and Zhao, Liming and Li, Xi and Wang, Xinchao and Tao, Dacheng_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Geometry-Aware_Scene_Text_CVPR_2018_paper.pdf)

###### Irregular text
1. __Detecting Curve Text in the Wild: New Dataset and New Solution.__ _Yuliang, Liu and Lianwen, Jin and Shuaitao, Zhang and Sheng, Zhang_. 2017 [paper](https://arxiv.org/abs/1712.02170)
2. __Mask TextSpotter: An End-to-End Trainable Neural Network for Spotting Text with Arbitrary Shapes.__ _Lyu, Pengyuan and Liao, Minghui and Yao, Cong and Wu, Wenhao and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Pengyuan_Lyu_Mask_TextSpotter_An_ECCV_2018_paper.pdf)
3. __TextSnake: A Flexible Representation for Detecting Text of Arbitrary Shapes.__ _Long, Shangbang and Ruan, Jiaqiang and Zhang, Wenjie and He, Xin and Wu, Wenhao and Yao, Cong_. 2018 [paper](https://link.springer.com/chapter/10.1007/978-3-030-01216-8_2)

###### Speed up
1. __EAST: An Efficient and Accurate Scene Text Detector.__ _Zhou, Xinyu and Yao, Cong and Wen, He and Wang, Yuzhi and Zhou, Shuchang and He, Weiran and Liang, Jiajun_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhou_EAST_An_Efficient_CVPR_2017_paper.pdf)

###### Easy instance segmentation
1. __Multi-scale FCN with Cascaded Instance Aware Segmentation for Arbitrary Oriented Word Spotting in the Wild.__ _He, Dafang and Yang, Xiao and Liang, Chen and Zhou, Zihan and Ororbia, Alexander G and Kifer, Daniel and Giles, C Lee_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/He_Multi-Scale_FCN_With_CVPR_2017_paper.pdf)
2. __Self-organized Text Detection with Minimal Post-processing via Border Learning.__ _Wu, Yue and Natarajan, Prem_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wu_Self-Organized_Text_Detection_ICCV_2017_paper.pdf)
3. __WordFence: Text Detection in Natural Images with Border Awareness.__ _Polzounov, Andrei and Ablavatski, Artsiom and Escalera, Sergio and Lu, Shijian and Cai, Jianfei_. 2017 [paper](https://arxiv.org/abs/1705.05483)
4. __PixelLink: Detecting Scene Text via Instance Segmentation.__ _Dan, Deng and Haifeng, Liu and  Xuelong, Li and Deng, Cai_. 2018 [paper](https://arxiv.org/abs/1801.01315)

###### Retrieving designated text
1. __Unambiguous text localization and retrieval for cluttered scenes.__ _Rong, Xuejian and Yi, Chucai and Tian, Yingli_. 2017 [paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Rong_Unambiguous_Text_Localization_CVPR_2017_paper.pdf)

###### Against complex background
1. __Single Shot Text Detector With Regional Attention.__ _He, Pan and Huang, Weilin and He, Tong and Zhu, Qile and Qiao, Yu and Li, Xiaolin_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/He_Single_Shot_Text_ICCV_2017_paper.pdf)

#### 2.2 Recognition

##### 2.2.1 CTC based methods
1. __Unconstrained on-line handwriting recognition with recurrent neural networks.__ _Graves, Alex and Liwicki, Marcus and Bunke, Horst and Schmidhuber, Jurgen and Fernandez, Santiago_. 2008 [paper](http://papers.nips.cc/paper/3213-unconstrained-on-line-handwriting-recognition-with)
2. __Accurate scene text recognition based on recurrent neural network.__ _Su, Bolan and Lu, Shijian_. 2014 [paper](https://link.springer.com/chapter/10.1007/978-3-319-16865-4_3)
3. __STAR-Net: A SpaTial Attention Residue Network for Scene Text Recognition.__ _Liu, Wei and Chen, Chaofeng and Wong, Kwan-Yee K and Su, Zhizhong and Han, Junyu_. 2016 [paper](https://pdfs.semanticscholar.org/1cc5/1b093378caa887d25f8d70001ee52874d948.pdf)
4. __An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition.__ _Shi, Baoguang and Bai, Xiang and Yao, Cong_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/7801919/)
5. __Reading Scene Text with Attention Convolutional Sequence Modeling.__ _Gao, Yunze and Chen, Yingying and Wang, Jinqiao and Lu, Hanqing_. 2017 [paper](https://arxiv.org/abs/1709.04303),
6. __Scene Text Recognition with Sliding Convolutional Character Models.__ _Yin, Fei and Wu, Yi-Chao and Zhang, Xu-Yao and Liu, Cheng-Lin_. 2017 [paper](https://arxiv.org/abs/1709.01727)


##### 2.2.2 Attention based methods
1. __Robust scene text recognition with automatic rectification.__ _Shi, Baoguang and Wang, Xinggang and Lyu, Pengyuan and Yao, Cong and Bai, Xiang_. 2016 [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Shi_Robust_Scene_Text_CVPR_2016_paper.html)
2. __Recursive recurrent nets with attention modeling for ocr in the wild.__ _Lee, Chen-Yu and Osindero, Simon_. 2016 [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Lee_Recursive_Recurrent_Nets_CVPR_2016_paper.html)
3. __Visual attention models for scene text recognition.__ _Ghosh, Suman K and Valveny, Ernest and Bagdanov, Andrew D_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8270089/)
4. __Focusing Attention: Towards Accurate Text Recognition in Natural Images.__ _Cheng, Zhanzhan and Bai, Fan and Xu, Yunlu and Zheng, Gang and Pu, Shiliang and Zhou, Shuigeng_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Cheng_Focusing_Attention_Towards_ICCV_2017_paper.pdf)
5. __Learning to Read Irregular Text with Attention Mechanisms.__ _Yang, Xiao and He, Dafang and Zhou, Zihan and Kifer, Daniel and Giles, C Lee_. 2017 [paper](http://www.ijcai.org/proceedings/2017/0458.pdf)
6. __Arbitrarily-Oriented Text Recognition.__ _Cheng, Zhanzhan and Liu, Xuyang and Bai, Fan and Niu, Yi and Pu, Shiliang and Zhou, Shuigeng_. 2017 [paper](https://arxiv.org/abs/1711.04226)
7. __SqueezedText: A Real-time Scene Text Recognition by Binary Convolutional Encoder-decoder Network.__ _Liu, Zichuan and Li, Yixing and Ren, Fengbo and Yu, Hao and Goh, Wangling_. 2018 [paper](https://ren-fengbo.lab.asu.edu/sites/default/files/16354-77074-1-pb.pdf)

#### 2.3 End-to-End Text Spotting
##### 2.3.1 Separately Trained Two-Stage Methods
1. __Reading text in the wild with convolutional neural networks.__ _Jaderberg, Max and Simonyan, Karen and Vedaldi, Andrea and Zisserman, Andrew_. 2016 [paper](https://link.springer.com/article/10.1007/s11263-015-0823-z)
2. __Synthetic data for text localisation in natural images.__ _Gupta, Ankush and Vedaldi, Andrea and Zisserman, Andrew_. 2016 [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Gupta_Synthetic_Data_for_CVPR_2016_paper.html)
3. __TextBoxes: A Fast Text Detector with a Single Deep Neural Network.__ _Liao, Minghui and Shi, Baoguang and Bai, Xiang and Wang, Xinggang and Liu, Wenyu_. 2017 [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14202/14295)

##### 2.3.2 Jointly Trained Two-Stage Methods
1. __SEE: Towards Semi-Supervised End-to-End Scene Text Recognition.__ _Bartz, Christian and Yang, Haojin and Meinel, Christoph_. 2017 [paper](https://arxiv.org/abs/1712.05404)
2. __Deep TextSpotter: An End-To-End Trainable Scene Text Localization and Recognition Framework.__ _Busta, Michal and Neumann, Lukas and Matas, Jiri_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Busta_Deep_TextSpotter_An_ICCV_2017_paper.pdf)
3. __Towards End-To-End Text Spotting With Convolutional Recurrent Neural Networks.__ _Li, Hui and Wang, Peng and Shen, Chunhua_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Li_Towards_End-To-End_Text_ICCV_2017_paper.pdf)
4. __An End-to-End TextSpotter With Explicit Alignment and Attention.__ _He, Tong and Tian, Zhi and Huang, Weilin and Shen, Chunhua and Qiao, Yu and Sun, Changming_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1390.pdf)
5. __FOTS: Fast Oriented Text Spotting with a Unified Network.__ _Liu, Xuebo and Liang, Ding and Yan, Shi and Chen, Dagui and Qiao, Yu and Yan, Junjie_. 2018 [paper](http://openaccess.thecvf.com/content_cvpr_2018/CameraReady/1699.pdf)
6. __Mask TextSpotter: An End-to-End Trainable Neural Network for Spotting Text with Arbitrary Shapes.__ _Lyu, Pengyuan and Liao, Minghui and Yao, Cong and Wu, Wenhao and Bai, Xiang_. 2018 [paper](http://openaccess.thecvf.com/content_ECCV_2018/papers/Pengyuan_Lyu_Mask_TextSpotter_An_ECCV_2018_paper.pdf)

#### 2.4 Auxilliary Techs

##### 2.4.1 Synthetic Data
1. __Synthetic data and artificial neural networks for natural scene text recognition.__ _Jaderberg, Max and Simonyan, Karen and Vedaldi, Andrea and Zisserman, Andrew_. 2014 [paper](https://arxiv.org/abs/1406.2227)
2. __Synthetic data for text localisation in natural images.__ _Gupta, Ankush and Vedaldi, Andrea and Zisserman, Andrew_. 2016 [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Gupta_Synthetic_Data_for_CVPR_2016_paper.html)
3. __Verisimilar Image Synthesis for Accurate Detection and Recognition of Texts in Scenes.__ _Zhan, Fangneng and Lu, Shijian and Xue, Chuhui_. 2018 [paper](https://link.springer.com/chapter/10.1007/978-3-030-01237-3_16)

##### 2.4.2 Bootstrapping
1. __Wetext: Scene text detection under weak supervision.__ _Tian, Shangxuan and Lu, Shijian and Li, Chongshou_. 2017 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Tian_WeText_Scene_Text_ICCV_2017_paper.pdf)
2. __weakly supervised text attention network for generating text proposals in scene images.__ _Rong, Li and MengYi, En and JianQiang, Li and HaiBin, Zhang_. 2017 [paper](https://ieeexplore.ieee.org/abstract/document/8269992/)
3. __Wordsup: Exploiting word annotations for character based text detection.__ _Hu, Han and Zhang, Chengquan and Luo, Yuxuan and Wang, Yuzhuo and Han, Junyu and Ding, Errui_. 2018 [paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Hu_WordSup_Exploiting_Word_ICCV_2017_paper.pdf)

##### 2.4.3 Deblurring
1. __Convolutional neural networks for direct text deblurring.__ _Hradis, Michal and Kotera, Jan and Zemcik, Pavel and Sroubek, Filip_. 2015 [paper](http://www.fit.vutbr.cz/research/pubs/habil.php.en?file=%2Fpub%2F10922%2Fhradis15CNNdeblurring.pdf&id=10922)
2. __A blind deconvolution model for scene text detection and recognition in video.__ _Khare, Vijeta and Shivakumara, Palaiahnakote and Raveendran, Paramesran and Blumenstein, Michael_. 2016 [paper](https://www.sciencedirect.com/science/article/pii/S003132031600011X)

##### 2.4.4 Context Information
1. __Could scene context be beneficial for scene text detection?__ _Zhu, Anna and Gao, Renwu and Uchida, Seiichi_. 2016 [paper](https://www.sciencedirect.com/science/article/pii/S0031320316300449)

##### 2.4.5 Adversarial Attack
1. __Adaptive Adversarial Attack on Scene Text Recognition.__ _Yuan, Xiaoyong and He, Pan and Li, Xiaolin Andy_. 2018 [paper](https://arxiv.org/abs/1807.03326)

### III. Datasets

| Dataset (Year) | Image Num (train/test) | Text Num (train/test) | Orientation| Language| Characteristics | Detection Task | Recognition Task |
|:------:|:------:|:------:|:------:|:------:|:------:|:------:|:------:|
|End2End|====|====|====|====|====|====|====|
| [ICDAR03 (2003)](http://www.iapr-tc11.org/mediawiki/index.php?title=ICDAR_2003_Robust_Reading_Competitions) | 509 (258/251) | 2276 (1110/1156) | Horizontal | En | - | ✓  | ✓ |
| [ICDAR13 Scene Text(2013)](http://dagdata.cvc.uab.es/icdar2013competition/) | 462 (229/233) | - (848/1095) | Horizontal | En | - | ✓ | ✓ |
| [ICDAR15 Incidental Text(2015)](http://rrc.cvc.uab.es/?ch=4&com=introduction) | 1500 (1000/500) | - (-/-) | Multi-Oriented | En |  Blur/Small/Defocused | ✓ | ✓ |
| [ICDAR17/RCTW(2017)](http://u-pat.org/ICDAR2017/program_competitions.php) | 12263 (8034/4229) | - (-/-) | Multi-Oriented | Chinese | - | ✓ | ✓ |
| [Total-Text (2017)](https://github.com/cs-chan/Total-Text-Dataset) | 1555 (1255/300) | - (-/-) | Multi-Oriented,  Curved | En, Ch | Irregular/polygon label | ✓ | ✓ | |
| [SVT (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=The_Street_View_Text_Dataset) | 350 (100/250) | 904 (257/647) | Horizontal| En| - | ✓ | ✓ |
| [KAIST (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=KAIST_Scene_Text_Database) | 3000 (-/-) | 5000 (-/-) | Horizontal| En, Ko| Distorted | ✓ | ✓ |
| [NEOCR (2011)](http://www.iapr-tc11.org/mediawiki/index.php?title=NEOCR:_Natural_Environment_OCR_Dataset) | 659 (-/-) | 5238 (-/-) | Multi-oriented| 8 langs| - | ✓ | ✓ |
| [CUTE (2014)](http://cs-chan.com/downloads_CUTE80_dataset.html) | 80 (-/80) | - (-/-) | Curved | En | - | ✓ | ✓ |
| [CTW (2017)](https://ctwdataset.github.io) |  32K ( 25K/6K) |  1M ( 812K/205K) | Multi-Oriented | Chinese |  Fine-grained annotation | ✓ | ✓ |
|Detection Only|====|====|====|====|====|====|====|
| [OSTD (2011)](http://media-lab.ccny.cuny.edu/wordpress/cyi/www/project_scenetextdetection.html) | 89 (-/-) | 218 (-/-) | Multi-oriented| En| - | ✓ | - |
| [MSRA-TD500 (2012)](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_(MSRA-TD500)) | 500 (300/200) | 1719 (1068/651) |  Multi-Oriented | En, Ch |  Long text | ✓ | - |
| [HUST-TR400 (2014)](http://mclab.eic.hust.edu.cn/UpLoadFiles/dataset/HUST-TR400.zip) | 400 (400/-) | - (-/-) |  Multi-Oriented | En, Ch |  Long text | ✓ | - |
| [ICDAR17/RRC-MLT(2017)](http://rrc.cvc.uab.es/?ch=8) | 18000 (9000/9000) | - (-/-) | Multi-Oriented |  9 langs | - | - | - |
| [CTW1500 (2017)](https://github.com/Yuliang-Liu/Curve-Text-Detector) | 1500 (1000/500) | - (-/-) | Multi-Oriented,  Curved | En | Bounding box with $14$ vertexes | ✓ | - |
|Recognition Only|====|====|====|====|====|====|====|
| [Char74k (2009)](http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/) | 74107 (-/-) | 74107 (-/-) | Horizontal| En, Kanada | Character label | - | ✓ |
| [IIIT 5K-Word (2012)](http://cvit.iiit.ac.in/projects/SceneTextUnderstanding/IIIT5K.html) | 5000 (-/-) | 5000 (2000/3000) | Horizontal| -| cropped | - | ✓ |
| [SVHN (2010)](http://www.iapr-tc11.org/mediawiki/index.php?title=The_Street_View_House_Numbers_(SVHN)_Dataset) | - (-/-) | 600000 (-/-) | Horizontal| -| House number digits | - | ✓ |
| SVTP (2013) | 639 (-/639) | - (-/-) |  | En | Distorted | - | ✓ |





