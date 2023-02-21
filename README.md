# Head-Pose-Estimation


at the end of the supervised machine learning course at ITI we have worked on Head Pose Estimator  project , the problem in this project is that we have 2d landmarks and we do not have the Z-Axis , so we have used machine learning to solve this problem and draw the yaw , pitch and roll axis on the face .



through this project I have worked with my hard worker friend Mustafa Mohamed to find a solution for this problem through those steps :



1-getting the dataset and extracting the features which are the x,y axis of each landmark of the face  and labels which are the yaw , pitch and roll for each image

2- Normalizing the features 

3- performing hyper parameter tuning using Grid search for the SVR model

4-getting the results and testing it on an image and a video

