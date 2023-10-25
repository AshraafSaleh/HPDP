<a href="https://github.com/drshahizan/BDM/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/BDM" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/BDM/network/members"><img src="https://img.shields.io/github/forks/drshahizan/BDM" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/BDM/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/BDM" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/BDM"><img src="https://img.shields.io/github/issues/drshahizan/BDM" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/BDM/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/BDM?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)

# Assignment 1a: Examination results

### Group Name: KHUCHIN

## Introduction

Google Sheets is a spreadsheet tool that is part of Google's free, web-based Google Docs Editors suite. Google Sheets is accessible as a web app, a mobile app for Android and iOS, and a desktop app for Google's ChromeOS. The software supports Microsoft Excel file formats. Many people, organizations, and corporations use Google Sheets as it provides many variety of features that Google Sheets has capabilities to make many kinds of data management and analytical jobs. Users can use the application to create and edit files online while interacting with other users in real-time. Edits are documented by the user who made them, as well as a revision history. 

One dataset has been chosen for data analysis based on the case study that was given which is the Examination Result dataset. The dataset contains six columns which are Id_no, Academic, Sports, Co-Curriculum, Test_1, and Test_2. By doing this case study, we will show how to make data analysis based on the dataset that has been given based on the case study to turn it from raw data to valuable data.

## Data preprocessing

### Import dataset to Google Sheets
1. Import the dataset (Dataset1.txt) to Google Sheets <a href=”https://docs.google.com/spreadsheets/d/1q5UVmeU4xmzsocV9yqeHlnukuoOLkBJZTEqH96sb3oc/edit?usp=sharing“>Dataset 1</a> by clicking File on the upper left corner tab and select Import.
<div align="center">
  <img src="https://github.com/drshahizan/HPDP/blob/main/assignment/submission/ass1/KHUCHIN/case_study1a/DP1.png" alt="Image description">
</div>

### Creating Column
5. Creating a new column P1 to P5 based on the guide below:
<div align="center">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/930d3b47-d949-4e3e-b009-d7a1d859e3de" alt="Image description">
</div>

6. The new column (P1-P5) must be calculated for each column based on the marks for each categories (refer table below). For example column P1 is taken from column B. All the marks received by students must be divided by the max mark (from table below) and multiply by 3.33:
<div align="center">   
<img src ="https://github.com/drshahizan/HPDP/assets/118237589/ea1f8809-23da-4b1b-83fa-60c3ec258483">
</div>

7. The calculation for each categories are shown below:
   
<div align="center">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/ebb52714-55fa-43e2-9a14-4947664b7021" alt="Image 1">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/4f6e014c-52ff-4571-b71a-fc0cb91888fc" alt="Image 2">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/09d18afe-cb57-499d-b7d9-02df23d9b94c" alt="Image 3">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/38a1450e-cf9f-4225-b19e-9d6e4f8df2dd" alt="Image 4">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/31da351c-0dd5-4f82-b709-0c5627be809a" alt="Image 5">
</div>


8. The rest in the column are calculated by double-clicking on the bottom right of the cell. Refer to the picture below:

<div align="center">
  <img src="https://github.com/drshahizan/HPDP/assets/118237589/ed360a0c-6810-46e1-8f6e-ae001d2b657a" alt="Image description">
</div>

### Three Highest Value

9. Get the top three highest value from the row by using simple formula as shown in the pictures below:

<div class="center-images">
    <img src="https://github.com/drshahizan/HPDP/assets/118237589/0911bd5e-4a5c-4804-82bb-017498677259" alt="Image 1">
    <img src="https://github.com/drshahizan/HPDP/assets/118237589/b37210a4-d4de-426e-8326-7f65ee782056" alt="Image 2">
    <img src="https://github.com/drshahizan/HPDP/assets/118237589/769ed382-82f9-41d1-acb3-2e6c230da1f0" alt="Image 3">
  </div>

10. The rest are calculated the same way as in Step 8.


## Analysis of the dataset

<div id="Google_Sheet_Dashboard" align="center">
<img src="https://github.com/drshahizan/HPDP/blob/main/assignment/submission/ass1/KHUCHIN/case_study1a/Google_Sheet_Dashboard.png" width="800"/>
</div>

Based on the dataset, which has a total of 112K records, we may conduct an analysis in which the lowest overall percent that a student receives is 14.82 and the maximum is 98.57, with an 83.75 gap between the two. The overall percentage for students is 69.36. In terms of grading, we may look at the distribution of grades based on the top three highest grades in the dataset, which have high percentages, while the top three lowest grades stand out:

Top Three Highest Grades:
1. A → 23,214 Students
2. B+ → 13,851 Students
3. B → 13,515

Top Three Lowest Grades:
1. E → 712
2. D- → 1,029 
3. D → 1,681

The percentage of students who pass is 63.30%, or 70,594 students, and the percentage of students who fail is 36.70%, or 40,925 students. Approximately half of the students passed the examination, while the remaining students did not meet the required standard to pass the examination.


## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/BDM/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)


