# InstanceSegmentation

1) We annotated dataset using Roboflow Platform and while making a project folder we choose Instance segmentation.

![Screenshot (199)](https://user-images.githubusercontent.com/79048783/206734515-be32103b-706c-406c-bdb3-8f7fc54356dd.png)

2) We export the dataset to yolov-7 Pytorch Format.

![Screenshot (200)](https://user-images.githubusercontent.com/79048783/206738129-9e35630e-6437-4bdd-abd2-42b2be6dd686.png)


3) Finally train the model by specifying the hyperparameters, configuration etc.


4)After Training download the best.pt file and run on your loacl computer.

    Steps for inference on mp4 video:
  
     i) clone repository on local machine using command
 
          !git clone https://github.com/RizwanMunawar/yolov7-segmentation.git
    
      ii) Go to home directory
   
          cd yolov7-segmentation
        
      iii) Download the requirements i.e, all libraries and imports using commad
   
          !pip install -r requirements.txt
        
      iv)Move the weights file 'best.pt' to yolov7-segmentation directory
   
       v) Finally run inference on video using command.
   
           !python3 segment/predict.py --weights best.pt --source "videopath.mp4"

# Scope of Improvements
i) We can see that accuracy of model on video is a bit less and possible reason for same is small size of dataset 

ii)If we increase the number of images in the dataset while training it will surely improve performance of model also we can

iii) Tune hyperparameters and compare the results on the same.


                                                  
                                                                #THANK YOU😊!


        
 
     
     
   

