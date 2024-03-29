# Contents
1. [Software Engineering](#software-engineering)
2. [Machine Learning and AI](#machine-learning-and-ai)
3. [Cyber Security](#cyber-security)

## Software Engineering

### Project 1: Toy Swap Mobile App
This is a cross platform mobile phone app developed using Xamarin forms. The app targets parents of young children who would rather swap unused children toys with another family, rather than buying a new toy at retail price from a toy distributor. The app is designed in an MVVM framework, and data persistence was supported through the implementation of a cloud service provider (Firebase Realtime Database).
- This project was completed with Coventry University.
- Time constraint = 4 weeks

### Project 1: Demonstration
[![Demo Link](https://img.youtube.com/vi/pGUIrtsMeps/maxresdefault.jpg)](https://youtu.be/pGUIrtsMeps)

### Project 2: First FAQ Website
A knowledge-base system where users can post and answer questions.
The core functionality consists of three screens: home page, login, add question.
- This project was completed with Coventry University.
- Time constraint = 4 weeks

### Project 2: Demonstration
[![Demo Link](https://img.youtube.com/vi/eIv7m94olt8/maxresdefault.jpg)](https://youtu.be/eIv7m94olt8)
---
## Machine Learning and A.I.

### Project 1: Mice Protein Classification
Repository Address: http://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression
Using to classical classification models to classify possible mutations in mice protein data.
- This project was completed with Coventry University.
- Time constraint = 4 weeks

### Project 1: Demonstration
[![Demo Link](https://img.youtube.com/vi/jQ4u4y8--IY/maxresdefault.jpg)](https://youtu.be/jQ4u4y8--IY)

### Project 2: FLC for Indoor Climates
I designed and implemented of a fuzzy logic system optimised by evolutionary computation for controlling the climate of rooms in university building. The Fuzzy Logic Controller (FLC) will receive crisp values as input and class them by the designed fuzzy representation, the fuzzy values represent the climate for each of the five monitored environmental variables. The system uses Mamdani rule inference to calculate a solution, producing a fuzzy output value for each actuator accordingly. The inference engine will determine the required solutions to maintain a suitable climate. A total of 25 different IFTHEN rules are used to describe the systems behaviour. The defuzzifier then translates these fuzzy output values into crisp values to be used by the respective control system. The FLC defuzzifies the output into a crisp value using the COG (Centre of Gravity) method. The Fuzzy logic system uses a MIMO (Multiple Input Multiple Output) structure.
- This project was completed with Coventry University.
- Time constraint = 4 weeks
![FLCimage](https://user-images.githubusercontent.com/56298476/209697117-f8a07908-e56d-4f98-a8e6-c5d04d5c3fc4.png)

### Project 3: Implementing Object Detection into Orna RPG
I attempted to develop a object detection feature that could be implemented into Orna RPG. Several object detection methods were tested on objects found on the Orna World Map. Two of the approaches implemented that achieved semi-functionality were, the SIFT approach and the template matching. The template matching approach accurately detected all 11 templates. The SIFT approach had similar results with 10 out of the 11 objects accurately detected. The multi-scale template matching and colour detection approaches didn't reach a functional state due to tight time constraints. The implementations with the highest performances could then be developed to function within the Orna RPG source code. In the long term, object detection could be implemented into the Orna RPG to improve the user experience. The approach could be implemented to specify to the players which enemies, NPCs, buildings are visible on the world map. This solution is ideally focused towards created an altered intuitive experience for "high-need" gamers.
- This project was completed with Coventry University.
- Time constraint = 2 weeks

![OrnaSift](https://user-images.githubusercontent.com/56298476/209700076-d72399a3-8a9f-476a-8d5d-b67c38ae8f05.png)
![OrnaTempMatch](https://user-images.githubusercontent.com/56298476/209700140-d394d722-45d4-4587-8c80-48fc644fb60a.png)

## Cyber Security

### Project 1: System Audit
This audit aims to highlight vulnerabilities within the web applications security so that if further measures need to be a taken to protect website from a real threat, they can be. The most disconcerting issues being the high risk and impact of SQL Injections; including the overwhelming presence of external content embedded within the website’s pages. For the static analysis, I chose to use was a code review; this is when the auditor looks at the code manually and searches for vulnerabilities.
The tools used for the dynamic analysis were more involved more automation than the static analysis tool. I conducted a web crawl and vulnerability scan using Skipfish. I tested query injections using sqlmap. The audit uncovered some various vulnerabilities, most sitting within the gap of medium risk with high impact. In the static analysis, the code review revealed a few issues with the security of user’s passwords and the ease at which user’s profiles can be accessed. In the dynamic analysis, SQL Map surprisingly didn’t reveal any query injection vulnerabilities. On the other hand, Skipfish unearthed multiple vulnerabilities, one high risk vulnerability ironically being a query injection. There are practices that could be put in place to prevent SQL injection attacks or mitigate the impact of such an attack. The first suggestion would be to generate a threat model for the web application (ideally this would be created during the design phase of the web application). The second suggestion would be to implement further input validation to all the input fields within the web application; not letting the query bypass authentication before checking the format, size, type, and range of the input.

### Project 2: Secure System Design
The designed platform will support different levels of access for users (Student, Staff, Admin) to reduce Insider Threat risks. Passwords will be sensibly encrypted reducing the risk and impact of Web App Attacks and Data Breaches. The requirements request that logging/analytics are stored with an OPTOUT option. The format of the SQL queries and the possible use of different database services like MongoDB will reduce the threat of a SQL injection attack. The collection of analytics and
cookies implements appropiate OPT-OUT features in compliance to GDPR regulations.
