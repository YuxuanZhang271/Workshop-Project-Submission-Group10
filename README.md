### [ Practice Module ] Project Submission: Group 10

**[ Project Naming ]** Intelligent_Reasoning_Systems-2025_09_24-AIS07FT-Group10-AI_Powered_Scheduling_System



## **SECTION 1: PROJECT TITLE**

### **AI-Powered Scheduling System**

<img src="ProjectReport/Project_Report LaTeX/Images/System/cover.png" alt="Cover">



## **SECTION 2: EXECUTIVE SUMMARY**

The AI-powered Scheduling System is a smart personal assistant built to address the failures of traditional, static scheduling tools. Where most calendars fail to adapt to a user's dynamic energy levels, stress, and changing priorities, this project provides a human-centered solution that optimizes for both productivity and well-being.

By analyzing a user's historical data (such as task completion rates, time usage, and self-reported stress/energy levels), the system generates personalized and adaptive schedules designed to reduce decision fatigue and prevent burnout.

**🚀Core Technical Features**

The system's intelligence is driven by a two-part reasoning engine:

**🧠 Task Evaluation Model**: The model that predicts the expected energy, pressure, and completion quality for any given task. It uses historical impact weights to learn from a user's past performance, ensuring its recommendations improve over time.

**📅 Scheduler**: A rule-based reasoning system that transforms the prioritized task list into a feasible and adaptive timetable. It intelligently handles fixed and flexible tasks, using a progressive fitting strategy and priority-based swapping to manage conflicts. A key feature is its ability to optimize the length and placement of rest periods to maximize user energy recovery.

The front-end includes a **weekly timetable**, **daily & weekly report📊**, and an **AI chatbot💬** which leverages an LLM to understand natural language and automatically create tasks, creating a seamless user experience. This project is designed for students and knowledge workers who need to balance complex schedules with a sustainable, healthy routine.



## **SECTION 3: PROJECT CONTRIBUTION**

| Name         | Student ID | Work Items | Email              |
|--------------|------------|------------|--------------------|
| Jin Keyi     | A0276819L  | xxx | e1133134@u.nus.edu |
| Ko Hung-Chi  | A0327344E  | xxx | e1539175@u.nus.edu |
| Sun Yuchen   | A0326248B  | xxx | e1538079@u.nus.edu |
| Zhang Yuxuan | A0285664N  | xxx | e1216649@u.nus.edu |
| Zhao Jiahui  | A0329852U  | xxx | e1554179@u.nus.edu |



## **SECTION 4: VIDEO OF SYSTEM & USE CASE DEMO**

Refer to `Video/Intelligent_Reasoning_Systems-2025_09-AIS07FT-Group10-AI_Powered_Scheduling_System.mp4`

xxx also youtube link



## **SECTION 5: USER GUIDE**

For some issues you may have, and more explicit introduction, please refer to `ProjectReport/User_Guide.pdf`

### Start Backend
    
```
(base) ./ % cd SystemCode/backend 
(base) ./SystemCode/backend % conda create -n env python=3.10 
(base) ./SystemCode/backend % conda activate env 
(env) ./SystemCode/backend % pip install -r requirement.txt 
(env) ./SystemCode/backend % uvicorn main:app --reload
```
    
### Start Frontend
        
```
./ % cd SystemCode/frontend 
./SystemCode/frontend % npm start
```

⚠️ **If you get any issues when setting up the environment, please refer to the *Troubleshooting* part in *User Guide*.**



## **SECTION 6: PROJECT REPORT / PAPER**

Refer to `ProjectReport/Project_Report.pdf`

Content of the report: 

1 Executive Summary <br>
2 Problem Description <br>
3 Solutions <br>
&emsp;&emsp; 3.1 Task Evaluation Model <br>
&emsp;&emsp;&emsp;&emsp; 3.1.1 Data Preparation <br>
&emsp;&emsp;&emsp;&emsp; 3.1.2 Feature Engineering <br>
&emsp;&emsp;&emsp;&emsp; 3.1.3 Model Training and Evaluation <br>
&emsp;&emsp;&emsp;&emsp; 3.1.4 Task Scoring and Application <br>
&emsp;&emsp; 3.2 Scheduler <br>
&emsp;&emsp;&emsp;&emsp; 3.2.1 Core Architecture and Logic <br>
&emsp;&emsp;&emsp;&emsp; 3.2.2 Rest Time Distribution <br>
&emsp;&emsp;&emsp;&emsp; 3.2.3 Historical Impact Integration <br>
&emsp;&emsp;&emsp;&emsp; 3.2.4 Computational Efficiency <br>
&emsp;&emsp; 3.3 System Development <br>
&emsp;&emsp;&emsp;&emsp; 3.3.1 Database <br>
&emsp;&emsp;&emsp;&emsp; 3.3.2 Backend <br>
&emsp;&emsp;&emsp;&emsp; 3.3.3 Frontend (System Introduction) <br>


<hr>
<img src="ProjectReport/Project_Report LaTeX/Images/Logos/nus.png" alt="Cover">
<img src="ProjectReport/Project_Report LaTeX/Images/Logos/iss.png" alt="Cover">
