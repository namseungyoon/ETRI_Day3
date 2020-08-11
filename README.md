# ETRI_Day3
# Knowledge distillation
# To do 
  - Change the loss function which composed with true label of image, student output and teacher output 
  - Teacher: Only inference. No Training
  - Student: Training 
  
# Teacher
  - Teacher Network which is pretrained on CIFAR10 will be provided 
  - Teacher shoudn't be updated when training. 

# Student 
  - Student will be trained based on teacher and true labels 
  - The maximum convergence value of the student's accuracy can be 80.
