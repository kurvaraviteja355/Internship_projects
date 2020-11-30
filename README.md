# Internship_projects
1. project to create Customer Segmentation for Arvato Financial Services
In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in 2 phases:

Use Unsupervised Learning to perform customer segmentation and identify clusters/segments from general population who best match mail-order company's customer base.

Use Supervised Learning to identify targets for marketing campaign of the mail-order company who could possibly become their customers.

Goal of this project is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.

# Objection Detection using Tensorflow  
-	To run the object detection online run jupyter notebook
o	If this command gives you errors try running conda install jupyter and try again
o	This will open a web page in your browser. Navigate to object_detection/colab_tutorials/object_detection_tutorial.py
o	When the new page opens, click on ‘Run All’ under the cells tab
-	To run it on local PC we have to make a few changes. We will use the old version of the object detection tutorial with some modifications due to the current version not working correctly yet. 
-	To use our webcam instead of detecting images we will need to download cv2. We have to download the wheel file from here
o	Download the wheel version that matches your version of python
