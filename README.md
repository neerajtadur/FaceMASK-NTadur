# FaceMASK-GIT
 Face Mask Detection
 Data Set: 
This dataset consists of 4095 images belonging to two classes:

with_mask: 2165 images
without_mask: 1930 images

PreRequisites:
All the dependencies and required libraries are included in the file requirements.txt

Installation:

1. Clone the repo:
$ git clone https://github.com/chandrikadeb7/Face-Mask-Detection.git

2. Change your directory to the cloned repo:
$ cd FaceMASK-NTadur

3. Create a Python virtual environment 'Test' and activate it:
conda create --name Test python=3.7.6 -y
conda activate Test

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required
$ pip3 install -r requirements.txt


Working:

Open terminal. Go into the cloned project directory and type the following command:

# Training 
$ python3 train_mask_detector.py --dataset dataset

# To Run the model on local webcam, type the following command
$ python3 detect_mask_video.py 



