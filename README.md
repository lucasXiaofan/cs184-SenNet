# cs184-SenNet

![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/6dff850e-85a9-44cc-8b36-2032a2ee4e08)
Group 17, final presentation 11/29 group 3 </br>
Dean Nguyen, 23445044, deanpn@uci.edu</br>
XiaoFan Lu, 44016122, xiaofl14@uci.edu </br>
## final report: 
https://docs.google.com/document/d/13d0RIUAwX_GD4tu60LHovjWf9XiHbCYsOrl5xRO-J5o/edit?usp=sharing


# Instruction to run our code: 
the easiest way to run our code is using kaggle notebook, because we have 20GB of training data
1. create an kaggle account
2. join the kaggle competition: https://www.kaggle.com/competitions/blood-vessel-segmentation
3. copy our inference code : https://www.kaggle.com/code/langzhelu/second-sennet-submission?scriptVersionId=154097255
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/9a712180-59fe-45c2-9c96-7f11f21f64e3)
   
4. then you can either submit the notebook to see the score, or go to sanity check session to see the model's prediction
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/a23eeb67-d1b2-4859-8784-a3d405a87c4d)
     submission

   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/2878d348-f9aa-4489-beb7-0220607e9574)
     model predictions
---
# Our inference code: 
we run all of our experiments on Kaggle, each training and inference code have different version, the notebook only shows the latest version, but you can check for different version : 
* our best score inference/submission code: 
https://www.kaggle.com/code/langzhelu/second-sennet-submission?scriptVersionId=154097255
---
# Our training code: 
* XiaoFan's training code with 800x800 patch:
https://www.kaggle.com/code/langzhelu/sennet-unet-secondversion
* Dean's Training code: 
https://www.kaggle.com/code/deanphamnguyen/sennet-hoa-train-unet-simple-baseline/notebook?scriptVersionId=154040430
* Dean's UNet with Attention and Patches 800 x 800 training code:
https://www.kaggle.com/deanphamnguyen/dean-attention-unet-patch
---
# Our dataset and model:
* our current best perform model:
https://www.kaggle.com/datasets/langzhelu/resnext-1-2-1-before-final-report/settings
* 800x800 patches on kidney 1 & 2 dataset: 
https://www.kaggle.com/datasets/langzhelu/800x800kidney2/settings

