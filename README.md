## Project Overview

Welcome to the Convolutional Neural Networks (CNN) project!
In this project, you will learn how to build a pipeline to process real-world, user-supplied images.
Given an image, your algorithm will predict the most likely locations where the image was taken.

![Sample Output](landmark_project/images/sample_landmark_output.png)

By completing this lab, you demonstrate your understanding of the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.

Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/nd101-c2-landmarks-starter.git
		cd nd101-c2-landmarks-starter/landmark_project
	```
2. Download the dataset included below in the "Dataset Info" section. Note that this will be provided for you if using the workspace in the Udacity classroom.
3. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook landmark.ipynb
	```

__NOTE:__ While some code has already been implemented to get you started, you will need to implement additional functionality to successfully answer all of the questions included in the notebook. __Unless requested, do not modify code that has already been included.__

__NOTE:__ In the notebook, you will need to train CNNs in PyTorch.  If your CNN is taking too long to train, feel free to pursue one of the options under the section __Accelerating the Training Process__ below.



## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen CNN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own:

### Classroom GPU Workspace

A GPU workspace is available from within the Udacity classroom. Make sure you save your notebook and any related files, then click on the "Enable" button next to the GPU hours.

### Amazon Web Services

You can also use Amazon Web Services to launch an EC2 GPU instance.

## Evaluation

Your project will be reviewed by a Udacity reviewer against the CNN project rubric (linked in the classroom).  Review the rubric thoroughly and self-evaluate your project before submission.  All criteria found in the rubric must meet specifications for you to pass.

## Project Submission

Your submission should consist of the github link to your repository.  Your repository should contain:
- The `landmark.ipynb` file with fully functional code, all code cells executed and displaying output, and all questions answered.
- An HTML or PDF export of the project notebook with the name `report.html` or `report.pdf`.

Please do __NOT__ include any of the project data sets provided in the `landmark_images/` folder.

### Ready to submit your project?

Click on the "Submit Project" button in the classroom and follow the instructions to submit!

## Dataset Info

The landmark images are a subset of the Google Landmarks Dataset v2. If you are using the
classroom workspace, the dataset is provided therein; otherwise it can be obtained using
[this link](https://udacity-dlnfd.s3-us-west-1.amazonaws.com/datasets/landmark_images.zip).

You can find license information for the full dataset [on Kaggle](https://www.kaggle.com/google/google-landmarks-dataset).
