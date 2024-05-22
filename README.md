This code is suitable for running in the google colab instead of the vscode beacuse we are installing a specified versions of the packages which are already present in the google colab so please run it on colab
pakages to install with the versions are given below

1) installations:

-> Python 3.10.12 
-> Now install the specified versions of the packages

!pip install --user opencv-python==4.8.1.78
!pip install --user numpy==1.25.2
!pip install --user tensorflow==2.15.0
!pip install --user tqdm==4.66.2
!pip install --user joblib==1.4.0


2) Datasets:
-> we provided two datasets of the images of the sizes below. you can use any of the below datasets
but for the size constriant we uploaded only one with the small data of images(10 images only )
you can increase the size of the images by adding in the below folder

* first_zero_dc_images (200 images actually but size constriant we included only 10 images)



3) Execution of the Code:

Serial code:
 -> put the dataset name in the code for the folder path for execution
 -> open Serial notebook install pakages and run the block cell to get the out put

Parallel code:
-> put the dataset name in the code for the folder path for the execution
-> open Parallel notebook and run the block cells to get output

4) The program Dos:

-> this program executes the data generation and processing in parallel using the openmp inbuilt library joblib in python 
-> so we get the out put fast due to the parallel execution


