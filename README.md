# Head-Pose-Estimation

Head pose estimation means detecting the position of a human head in the image. Particularly, it means detecting the head’s Euler angles – yaw, pitch and roll. They define the object’s rotation in a 3D environment. If you make the right prediction about these three, you’ll find out which direction the human head will be facing.

## Tools Used

* Jupyter Notebook Python
* Google Colab
* Python
* mediapipe
* OpenCV

## Steps
* Download the AFLW2000-3D => [Link!](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/Database/AFLW2000-3D.zip )
* Get Face Mesh points 
* Get the labels from the (.mat) file of each image in the dataset
* Draw the 3-axis for the images => (yaw, pitch, roll)
* Collecting all these data in one dataframe
* Traing the model to predict the 3-axis
* Use Live stream to test the model in real videos

## Author 

* [Noha Aahed](https://github.com/nohaahed)
