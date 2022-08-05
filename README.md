# NBbirdsong
Birdsong detection

These files will create a convolutional neural network detection model for any bird species.

The file 'just_generate_dataset' will download every example of an input bird species from the cite xeno-canto.org. It then will guide you through selecting the birdsong you wish to make a dataset for. In step a), select the region of interest. In steps b) and c), find matching calls within the downloaded recordings.

![Template_process(1)(1)](https://user-images.githubusercontent.com/47158858/183220145-003a8fd8-4fe8-4d16-abd3-c45c73104722.png)

The file 'just_model' will take in the dataset you created, and make a CNN model for it. Finally, the file 'just_predict' will take in a recording that you input, process it, and out put the call count and call times for the species you trained for!
