## How to run the project

To run the program creat a .venv python environment. After that run the `pip install -r requirements.txt` command in the root folder of the project to install all the required libraries for the project. 

Download Datasets from this link [Google Drive](https://drive.google.com/drive/folders/1PcVrLhA2VeKSt_f4iKDWA5arnn9Ap4nF?usp=sharing) and  heavy street noise file and the  put them `recordings`, `393484__freetousesounds__authentic-street-sound-cambodia.wav` and the `test_recordings` folders in the root folder of your project

The first two scripts in the Jupyter Notebook `cw1.ipynb` file are for the training/validation and test dataset collection

There are two noise profiles, The White noise profile and the Heavy Streen noise profile. You can start by running training and testing the white noise profile then also test with heavy street noise profile, you will see that the model is still able to recognise the names with a `63% `accuracy in the heavy noise profile. Considering this is heavy street noise, its good. With the White noise profile, the model perfoms exceptionally well with an accuracy of `95%`. Overally the program is a success.