# Timezone - Timezone conversion utility

A command line utility in Node.js that performs timezone conversion.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Acknowledgements](#acknowledgements)


## General Information
A new project was created using npm, a third party dependency (moment.js) was installed and used in code to achieve the desired functionality.
This utility takes a timezone as a command line argument and tells the user the current time in that particular time zone. 


## Technologies Used
- node.js


## Screenshots
![Screenshot 2022-08-12 at 1 39 31 PM](https://user-images.githubusercontent.com/20161096/184346733-2abe7d1c-9367-4dc9-a332-2ac105204b0e.png)



## Setup & Usage

Clone this repo to your desktop and run `npm install moment` and `npm install moment-timezone` to install all the dependencies. 
Go to its root directory and run `node.js [filename] [Timezone]`.<br>
Eg: `node.js index.js 'Asia/Kolkata'`
The code looks for timezone as the third argument on the command line and handles error usecases involving incorrect number of arguments passed.



## Acknowledgements

- This project was part of a project on [JavaBrains's](https://javabrains.io) node.js course.
