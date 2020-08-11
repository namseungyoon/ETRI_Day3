# ETRI_Day3
# Knowledge distillation
# To do 
  - Change the loss function which composed with true label of image, student output and teacher output 
  - Teacher: Only inference. No Training
  - Student: Training 
  
  ![캡처](https://user-images.githubusercontent.com/55013577/89905415-1e641e80-dc25-11ea-863c-16248ecb3281.PNG width="70%")
  
# Teacher
  - Teacher Network which is pretrained on CIFAR10 will be provided 
  - Teacher shoudn't be updated when training. 

# Student 
  - Student will be trained based on teacher and true labels 
  - The maximum convergence value of the student's accuracy can be 80.
