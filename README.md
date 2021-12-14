# Traffic_Sign_Detection

**About Files in this repository**

**1. myData folder**

     Contains 43 sub folders starting from 0 and ending at 42. Each subfolder has images of relevant classs. 
     Eg. subfolder named 0 has images of speed limit 20

**2. label.csv**

     This file contains label for each subfolder.
     Eg. subfolder 0 has a label "Speed limit (20km/h)" and subfolder 1 has a label "Speed limit (30km/h) and so on

**3. model_trained.p**
     
     This is a pickle file which stores parameters of trained model that can be reused 
     
**4. TraficSign_Main.py**

     This is the python file that contains code for training the model. 
     
     
**5. TrafficSign_Test.py**

     This python file contains code to test the model
     

**About Dataset and Model performance**

**1. Dataset information**

     Total images - 34791
     Color band   - 3 (Red, Green, Blue)
     Image size   - 32 * 32
     Total number of classes - 43
     Training set size   - 22271 images
     Validation ser size - 5568  images
     Test set size       - 6960  images
     
 **2. About Model**
 
      Model used - Convolutional Neural Network
      Probability Threshold - 75%
     
     
