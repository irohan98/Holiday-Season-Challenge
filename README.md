# Holiday-Season-Challenge

# HackerEarth Deep Learning Challenge: 'Tis STILL the season to be jolly

### Problem statement
You work for a social media platform. Your task is to create a solution using deep learning to discern whether a post is holiday-related in an effort to better monetize the platform.

### Task
You are given the following six categories. You are required to classify the images in the dataset based on these categories.
 - Miscellaneous
 - Christmas_Tree
 - Jacket
 - Candle
 - Airplane
 - Snowman
 
### Data Description
This data set consists of the following two columns namely Column name and Description

### Data Format
The data folder consists of two folders and one .csv file. The details are as follows:
train: Contains 6469 images for 6 classes
test: Contains 3489 images
train.csv: 3489 x 2

### Submission Format
You are required to write your predictions in a .csv file

### Sample Submission
Image, Class
image3476.jpg, Miscellaneous
image5198.jpg, Candle
image4183.jpg, Snowman
image1806.jpg, Miscellaneous
image7831.jpg, Miscellaneous

### Evaluation Matrice
score = {100* f1_score(actual_values,predicted_values,average = 'weighted')}
 
### Acknowledgement
Link To Contest --> https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-holidays/

---
# My Solution (Rank: 76, Top 3%)
- SCORE: 92.38196
(https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-holidays/leaderboard/holiday-season-11-2c924626/page/2/)
- Used transfer learning in Keras and fine-tuned an InceptionResNetV2 model

