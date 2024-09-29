# Predict Online Course Engagement

This project aims to predict user engagement in online courses using machine learning techniques. By analyzing historical user data, we can predict whether users will complete a course based on various features like time spent, quiz performance, and video consumption patterns.

## Project Overview
With the increasing popularity of online education platforms, understanding and predicting user engagement is crucial. The goal of this project is to build a predictive model to identify users who are likely to complete a course and those who might drop out. This information can help educators and course creators improve retention rates and create personalized interventions.

## Dataset
The dataset contains user activity from various online courses, including metrics related to course completion, video watching habits, quiz performance, and more.

| Column Name              | Description                                                    |
|--------------------------|----------------------------------------------------------------|
| `CourseCategory`         | Category of the course (e.g., Programming, Design, Business).  |
| `TimeSpentOnCourse`      | Total hours spent on the course.                               |
| `NumberOfVideosWatched`  | Number of videos watched by the user.                          |
| `NumberOfQuizzesTaken`   | Number of quizzes taken.                                       |
| `QuizScores`             | Average quiz scores.                                           |
| `CompletionRate`         | Percentage of the course completed by the user.                |
| `DeviceType`             | Device used (1 = mobile, 2 = desktop).                         |
| `CourseCompletion`       | Target variable: 1 if the course is completed, 0 otherwise.    |
