# cs184-SenNet

![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/6c93d9f5-e821-4917-bbb3-69545ec2d049)

Group 17, final presentation 11/29 group 3 </br>
Dean Nguyen, 23445044, deanpn@uci.edu</br>
XiaoFan Lu, 44016122, xiaofl14@uci.edu </br>
# final report
https://docs.google.com/document/d/13d0RIUAwX_GD4tu60LHovjWf9XiHbCYsOrl5xRO-J5o/edit?usp=sharing
---
# check our code locally
* due to kaggle competition rule, the data is only available to competition participant, so we did not download the competition dataset for training and inference, however there are output in the notebook we provide, you may check the prediction of our project.
* if you have your own CT-kideny images, you may try our inference code 
and change file direction to examine the prediction. 

---
# Our inference code: 
we run all of our experiments on Kaggle, each training and inference code have different version, the notebook only shows the latest version, but you can check for different version : 
* our best score 0.519 inference/submission code:
https://www.kaggle.com/deanphamnguyen/second-sennet-submission-c96555
* inference with 0.404: 
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
## you can download our current best score (0.519) weight bin on github and upload it to our Kaggle inference notebook "U_net_with_attention.bin"
* LB 0.404, model:
https://www.kaggle.com/datasets/langzhelu/resnext-1-2-1-before-final-report/settings
* 800x800 patches on kidney 1 & 2 dataset: 
https://www.kaggle.com/datasets/langzhelu/800x800kidney2/settings
---
# ✨Instruction to run our code: 
the easiest way to run our code is using kaggle notebook, because **according to Kaggle competition's rule: before SenNet Competition finish, the competition's data may only show to people who participate in competition**, plus we have 20GB of training data
## 1. create an kaggle account
## 2. join the kaggle competition: https://www.kaggle.com/competitions/blood-vessel-segmentation
## 3. copy our inference code : https://www.kaggle.com/deanphamnguyen/second-sennet-submission-c96555
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/9a712180-59fe-45c2-9c96-7f11f21f64e3)
## 4. download the "U_net_with_attention.bin" from our github, and upload the bin to kaggle as your dataset
### 1. upload file to Kaggle
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/47f38b96-0433-4216-8c5e-f33e7f94ecce)
### 2. upload the weight bin
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/883481db-6cde-4bfd-82ec-4715718fda6b)
### 3. create your own kaggle dataset
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/9271f1d3-6da9-4b65-ade0-88e7e2d6b28d)
### 4. copy the weight bin path
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/8ab62646-fbfd-4776-b13a-939f85fc64c0)
### 6. search for CFG and paste the weight bin path to update the bin_path
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/59ae2940-9a47-49d7-84f6-76e634b78224)

## 5. then you can either submit the notebook to see the score, or go to sanity check session to see the model's prediction
   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/a23eeb67-d1b2-4859-8784-a3d405a87c4d)
     submission

   ![image](https://github.com/lucasXiaofan/cs184-SenNet/assets/91307310/2878d348-f9aa-4489-beb7-0220607e9574)
     model predictions


