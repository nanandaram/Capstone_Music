# Capstone_Music
This project aims to classify the music into their own genres 

Outline of the process.

1. There are 1000 music files stored in Data direcorty
2. Libroso_file.ipynb ( librosa lib) extarct sthe feaures for these music files and create features in data.xls file.
   It also creates specral image data stores in img_data direcory
3. Music_testing_and_traing.ipynb file reads the data.xls to rul modles for genre classification.
4. Project presentaion is avaiable in the " Project_presentation.ppt" file.


Personal goal for choosing this project
1. To learn modeling in python
2. To learn the process involved in projects that does not have features/data readlily avaiable

Challenges.
1. I was able to find and EC2 image with 1M music data 
2. Dint have enough personal compute power to run the librosa on that large volume of data 
3. I couldnt run the first 10k files on EC2 as I maxed out the storage required for free tier, and eded up paying 
4. Had stick to 1000 records both form personal compute and AWS point of view. 





