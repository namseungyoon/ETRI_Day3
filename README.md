# ETRI_Day3
# Knowledge distillation
# To do 
  - Change the loss function which composed with true label of image, student output and teacher output 
  - Teacher: Only inference. No Training
  - Student: Training 
![distill_loss](https://user-images.githubusercontent.com/55013577/89907697-f2966800-dc27-11ea-8a62-b71d05e60cb2.PNG)
  
  
# Teacher: VGG 16 (pretrained on CIFAR 10 dataset) 
  - Teacher Network which is pretrained on CIFAR10 will be provided 
  - Teacher shoudn't be updated when training. 

# Student: N layer CNN(have to implement)
  - Student will be trained based on teacher and true labels 
  - The maximum convergence value of the student's accuracy can be 80.
