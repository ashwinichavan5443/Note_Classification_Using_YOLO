# Note_Classification_Using_YOLO
<b>Step1: Collect dataset and label required object using labelImg tool </b><br>https://github.com/tzutalin/labelImg<br>
<b>Step2: Click on create new dataset and upload images on dataset on roboflow website</b><br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t1.jpg"></img><br>
-	give dataset name and labeling classes<br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t2.jpg"></img><br>
-	Click on select file button and upload images and its XML files. Once done with uploading click on finish
https://public.roboflow.com/
-	It will resize image according to given specification and we can choose darknet or mobile etc. according to Algorithm we used for training model for V4 tiny choose darknet and image size 416X416
-	Click on select file button and upload images and its XML files. Once done with uploading click on finish<br>
https://public.roboflow.com/<br>
-	It will resize image according to given specification and we can choose darknet or mobile etc. according to Algorithm we used for training model for V4 tiny choose darknet and image size 416X416<br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t3.jpg"></img><br>
-	After completion click on download click on generate button<br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t4.jpg"></img><br>
-	Again click on generate button<br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t5.jpg"></img><br>
-	From dropdown menu select Darknet format and select show download code option click on continue
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t6.jpg"></img><br>
-	Copy dataset link from here <br><b>Step 3: Open YOLO_V4_tiny_customtrain.ipynb colab book</b><br>
<img src="https://github.com/ashwinichavan5443/Note_Classification_Using_YOLO/blob/master/t7.jpg"></img><br>
-	Past that link here inside inverted quotes <br><b>Step 4: run each cell from beginning as it is<b></br>
<b>Step 5: Once training is done download go to darknet > backup > . inside this download best model
Form darknet > cnf folder download config file From darknet> data folder obj.data and obj.name</b>




