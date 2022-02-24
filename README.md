# Realtime-data-labeling-for-creating-custom-datadets-for-object-detection

 It is recomended to create a folder called Data and two sub folders called images and labels where real time captured images
 are stored in images folders and their corresponding labels are stored in labels folder .
 
 labels=['class1','class2'] # u can mention diffrent types of classed for example happy, sad etc
 number of classes can be added or reduced in this line of code for example 
 for a code like emotions detector we can add classes like 'happy','sad','angry' etc and collect images accordingly
 
number_imgs = 20 #mention no of images to be collected per class
as the no of images increased the accuracy of prediction increases. so the number of images to be captured can be changed from here 
 
