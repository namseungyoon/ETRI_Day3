# ETRI_Day3
# Knowledge distillation
## VGG.py: Teacher Network 
## VGG16_teacher.pth: pretrained weights 
## download the pretrained weight in google drive: https://drive.google.com/drive/folders/16XDhtJIvLURY922JYmuetgoyGwcli2lW?usp=sharing


# To do 
 Change the loss function which composed with true label of image, student output and teacher output 
  # Teacher: VGG 16 (pretrained on CIFAR 10 dataset) 
    - Teacher Network which is pretrained on CIFAR10 will be provided 
    - Teacher shoudn't be updated when training. (Evaluation mode) 

  # Student: 5 layer CNN(have to implement)
    - Student will be trained based on teacher and true labels
      - The architecture of Student model is up to you. 
      - And train the student network 
<img width="1362" alt="캡처" src="https://user-images.githubusercontent.com/55013577/89967023-6322a080-dc8b-11ea-934b-fe6ea0110b61.PNG">

![zoqcj](https://user-images.githubusercontent.com/55013577/89912145-2d4ecf00-dc2d-11ea-9120-67484e3306f7.PNG)  
  



