# Smart Watch/Phone App

![](https://github.com/asikhalaban/Smart-Watch-Phone-App/blob/master/img/smart-phone-app-650.jpg)

In This Github, I want to share some of my experience regarding to an app that I'm developing for smartwatch and smartphone. Unfortunately, I'm not able to share whole my algorithm and code but I try my best to explain the most important and difficult part of SmartWatch application and Deeplearning that could be useful for other projects.But, my main focus is on ETL and analyzing dataset from smart watch/phone app.   
You can reach me at my email asikhalaban@gmail.com for any questions or suggestions.

## Table of Contents

#### 1. Introduction<br>
[a. A Road Map for Reader and Structures](#structures) 
#### 2. ETL Data FROM Smartwatch<br>
[a. Introduction to the Application](#Introduction) <br>
[b. About the extracted Dataset and Features](#Introduction)  
#### 3. Machine Learning Application<br>
#### 4. Deep Learning Tool<br>
<br><br><br><br><br><br>


## 1. Introduction
<a name="structures"/>
### a. A Road Map for Reader and Structures

As I mentioned earlier in this Github I cannot share whole my project and algorithm but I try my best to share my experience through this project. Are you intereted to know about my project? It is about detection some human motion analysis from smartwatch sensors by using Machine Learning and Deep Learning.

In next chapter, you can see the methods and features that I selected to collect and extract data from smartwatch. In chapter 3, I explained some of machine learning methods and my experience regarding to analyze data and signals from previous chapter. In the last chapter, I don't know still do I have to add it or not :D 

Again, please contact me either on asikhalaban@gmail.com or asikhalaban@yahoo.com for any questions or suggestions. Working Hard and Have Fun! ;)

<br><br>

## 2. ETL Data FROM Smartwatch
<a name="Introduction"/>
### a. Introduction to the Application

This application is developed to collect dataset from Android smartwatch by using Java. I didn't bring the code and explaination here because I'm not that much professional in Java and I got help from my friends to develop this part and I cannot explain very well how the code is working or teach something very important for other developer but if you are interested to know how did I collect data from smartwatch you can email me(asikhalaban@gmail.com). This link could be very useful and helpful for your application [Android Developers Page](https://developer.android.com/guide/topics/sensors/sensors_overview.html).

The smartwatch application is collecting several features from different sensors such as: 
TYPE_ROTATION_VECTOR
TYPE_ORIENTATION
TYPE_GRAVITY
TYPE_LINEAR_ACCELERATION
You can find about each feature from [Android Developers Page](https://developer.android.com/guide/topics/sensors/sensors_overview.html).
Each specified time the application sends those selected feature to a smartphone and the smartphone is recording those features as a text file.

One of the problem that I got here is installing the apk on smart watch and phone. 
To install apk on smart watch and phone, first you have to turn on developer 


