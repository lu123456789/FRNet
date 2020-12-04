# FRNet: Factorized and Regular Blocks Network for Semantic Segmentation in Road Scene  
## **Published in: IEEE Transactions on Intelligent Transportation Systems (IEEE TITS)**  
This project contains the Pytorch model for the proposed FRNet: http://dx.doi.org/10.1109/TITS.2020.3037727  
pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9275365  

## **Results**  
| Dataset | Pretrained  | mIoU | FPS  |  train size |  
| :------------ |:---------------:| -----:| -----:| -----:|    
| Cityscapes    | from scratch | 70.4 | 127 |  512×1024  |    
| Camvid        | from scratch | 67.4 | 183 |  256×256   |
| Kitti         | from scratch | 92.5 | 152 |  256,800   |  
| Gatech        | from scratch |  -   | 176 |  256,480   |  

## **Citation**  
Please consider citing the FRNet if it's helpful for your research.  

@ARTICLE{9275365,  author={M. {Lu} and Z. {Chen} and Q. M. J. {Wu} and N. {Wang} and X. {Rong} and X. {Yan}},    
journal={IEEE Transactions on Intelligent Transportation Systems},     
title={FRNet: Factorized and Regular Blocks Network for Semantic Segmentation in Road Scene},     
year={2020},    
volume={},    
number={},    
pages={1-9},    
doi={10.1109/TITS.2020.3037727}}  
