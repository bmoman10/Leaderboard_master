# Leaderboard

The leaderboard is an interactive scoreboard that displays scores of either individual assigments or totals for all students in a specified course. Below is a screenshot of what to expect when using the leaderboard.

![leaderboardss](https://user-images.githubusercontent.com/25061149/28384066-ea7a01ca-6c88-11e7-97ec-064833a428b2.png)

First you'll notice two drop down menus.

Start by selecting the course and under the "column" drop down menu on the right you'll select either "total" or an individual assignment.

Just below the drop down menus the course information is displayed with information on the selected course's term as well as the number of students enrolled.

A bar graph is displayed for the selected course and assignment.

The bars represent individual students scores compared to other students.

To display the student associated with a specific bar, simply click on the bar and the student's information will be displayed below.

# Code Example

![databasess](https://user-images.githubusercontent.com/25061149/28385298-36fece3c-6c8d-11e7-94ba-fac0f2b63ed0.png)

The database class accepts a java interface named "DataSource". This allows new sources of data to be easily supported by simply creating a new interface or modifying an existing one.

In each of the DataSource interfaces, the information is correctly sorted/rearranged to fit the specifications the program needs to perform properly.

There is currently a FileSource interface that supports .csv and .json files as well as a WebSource interface that supports .json files.

# Testing

Testing is done by using the included .ROBOT files and running the "gradle runrobot" command within the root folder. This will automatically perform several tasks and return results after completion. Below is an example of one of the robot tests.


![robotss](https://user-images.githubusercontent.com/25061149/28386236-911046be-6c90-11e7-9d2f-dc2eb0e35e02.png)


# Motivation

This was a collaborative project made by myself and 5 other group members part of my software engineering I class at JSU. This was our first experience working together as part of a group using the agile process scrum. We were tasked with adding 7 features over the semester. We successfully passed all tests given and recieved and A for this project.

# Libraries and Resources

- Gradle Build Tool
- Maven Repositories
  - "org.json:json:20160810"
  - 'com.googlecode.json-simple:json-simple:1.1.1'
  - 'org.jfree:jfreechart:1.0.19'
  - "gradle.plugin.org.roboscratch.gradle:gradle-robot:0.1.1"
  - "org.robotframework:swinglibrary:1.9.6"
  - "org.robotframework:javalib-core:1.2.1"
  - "net.sf.opencsv:opencsv:2.3"
