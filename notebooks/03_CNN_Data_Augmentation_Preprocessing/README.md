This `README.md` will take you through the steps to be able to create the dataset where the notebook `03_CNN_Data_Augmentation_Preprocessing.ipynb` is dependent on.


1. Download the the following file from https://www.kaggle.com/c/dogs-vs-cats/data:

* `train.zip`

*Note: The following filename may change in that kaggle source. Adjust the commands that follow
according to the new filename (if necessary).*

2. Upload in your jojie/local directory of this repository (use this path: `msds2022-ml3/notebooks/03_CNN_Data_Augmentation_Preprocessing/`)

3. Using the terminal, navigate to the `03_CNN_Data_Augmentation_Preprocessing` directory using the Linux `cd` command.

Example: `cd ~/msds2022_ml3/notebooks/03_CNN_Data_Augmentation_Preprocessing`

4. Unzip the files within this same directory using the `unzip` package. This will create the `train` directory containing all the image files. *Note: **DO NOT** attempt to open (click) the directories as it may crash your browser due to the number of files they contain.*

Example: `unzip train.zip`

5. Rename the `train` directory to `dogs_vs_cats` using the move `mv` command:

Example: `mv train dogs_vs_cats`

5. Check file counts by piping the list command `ls` to the `wc` command.

Example: `ls dogs_vs_cats | wc -l` should return 25,000 (number of combined cats and dogs images in the original training set)

6. Proceed with running the notebook `03_CNN_Data_Augmentation_Preprocessing.ipynb`. New directories will be created using the `python` commands in the notebook.