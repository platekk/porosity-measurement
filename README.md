# Porosity measurement

This code was created to measure percentage of porosity in thermally sprayed coatings.
To run, save (i) "porosity_local" or (ii) "porosity_gdrive" file and open using (i) local software or (ii) [Google Colab](https://colab.research.google.com/?hl=pl). 


As input, SEM image with default dimension of 1224x2048 or 1224x1024 are used.

[<img src="https://github.com/platekk/porosity-measurement/assets/148436343/5c815c2e-b7cb-4983-83fa-72993acc268c" width="500"/>]([![image](https://github.com/platekk/porosity-measurement/assets/148436343/6ab761c2-88e5-48ba-87f9-c19b8641474f))
<em>Examplary input image</em>


All photos should be placed in the same folder, stored on local disc (porosity_local) or Google Drive (porosity_gdrive). Additionally, Excel fille (file_name.xlsx) for output storege should be also created and - in case of GDrive version - imported to Google Drive. Both images folder and excel file should be placed in same location (same folder). All analyzed images should present the same sample and be made with the same contrast and brightess settings. 

Before measurement, adjustment of cropping, contrast and treshold settings will be carried out on random image selected from the folder. 
As a result, mean porosity value with standard deviation will be printed. Detailed data about porosity value measured for each image will be stored in excel file with corresponding image name. 

[<img src="https://github.com/platekk/porosity-measurement/assets/148436343/484b5f63-b370-40b8-8949-ef905d1f09f2" width="250"/>]([image.png](https://github.com/platekk/porosity-measurement/assets/148436343/484b5f63-b370-40b8-8949-ef905d1f09f2)) 
<em>Input image</em>

[<img src="https://github.com/platekk/porosity-measurement/assets/148436343/5a3865a1-8f4d-46cd-a0d1-d7f8d2cbb823" width="250"/>]([image.png](https://github.com/platekk/porosity-measurement/assets/148436343/5a3865a1-8f4d-46cd-a0d1-d7f8d2cbb823))
<em>Thresholding</em>

