### [ Practice Module ] Project Submission: Group 10

**[ Intelligent_Reasoning_Systems-2025_09_24-AIS07FT-Group10-AI_Powered_Scheduling_System ]** 



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

Refer to `ProjectReport/Individual_Contribution.pdf`

| Name         | Student ID | Work Items | Email              |
|--------------|------------|------------|--------------------|
| Jin Keyi     | A0276819L  | **1. Contributions** <br> (1) During the system design phase, resolved several scheduler rule–related issues, ensuring logical consistency and robustness in the scheduling mechanism. <br> (2) Developed the backend architecture, established MongoDB connections, and implemented core functionalities including user and task management with credential verification. <br> (3) Designed and trained the Task Evaluation Model, experimenting with multiple machine learning algorithms to enhance prediction accuracy. <br> (4) Handled data preprocessing and feature engineering to ensure high-quality model input and optimal system performance. <br><br> **2. Self-Reflection** <br> Through this project, I deepened my understanding of backend development and machine learning integration. I learned how to balance system design efficiency with model performance and gained valuable experience in handling real-world data and improving model accuracy through iterative experimentation and optimization. | e1133134@u.nus.edu |
| Ko Hung-Chi  | A0327344E  | **1. Contributions** <br> (1) UI Design: Designed the complete user interface for the scheduling system, defining the visual layout, user workflow, and interaction elements. <br> (2) Frontend Development: Co-developed the frontend code, translating the UI designs into a functional, interactive application for users. <br> (3) Backend Integration: Helped integration of frontend to the backend, enabling data flow between the user interface. <br> (4) Chatbot Prompt Engineering: Handled prompt engineering for the AI chatbot, structuring queries to accurately extract task parameters from natural language inputs. <br> (5) Video Production: Edited the final project demonstration video, compiling footage to effectively showcase the system's features and overall functionality. <br><br> **2. Self-Reflection** <br> As my undergraduate background isn’t in this discipline, this project presented a learning curve. The work required close collaboration to connect the frontend with the backend. In UI design and frontend development, I learned how the data flow works real-time, ensuring the interface could correctly send user inputs to the backend and display the generated schedule. Integrating the AI components was also a challenge. Through prompt engineering, I learned how to structure prompt for the LLM and how that data was subsequently fed into the scheduler. This project provided understanding of applying predictive models and LLMs in intelligent system. | e1539175@u.nus.edu |
| Sun Yuchen   | A0326248B  | **1. Contributions** <br> (1) Responsible for frontend page design and implementation, ensuring a smooth and intuitive user interface for task creation, editing, and visualization. <br> (2) Managed frontend–backend integration with a FastAPI-based backend to enable real-time task updates and synchronization. <br> (3) Participated in model training for the Task Evaluation Module. <br> (4) Modified parts of the backend logic for task scheduling and the AI chatbot. <br> (5) Ensured consistent communication and data flow between different system modules. <br> (6) Contributed to project documentation, including writing and revising key sections of the final report. <br><br> **2. Self-Reflection** <br> Through this project, I gained comprehensive experience in full-stack development and the integration of AI models into practical applications. Working on both frontend and part of backend components enhanced my understanding of system architecture, API design, and model deployment. I also learned to manage version control and collaborate efficiently within a multi-member team. The process of debugging cross-module interactions and optimizing model performance improved my problem-solving skills. Overall, this project strengthened my technical depth and teamwork abilities, reinforcing my interest in building intelligent, human-centered AI systems. | e1538079@u.nus.edu |
| Zhang Yuxuan | A0285664N  | **1. Contributions** <br> (1) Served as Team Leader, coordinating overall project progress and team collaboration. <br> (2) Proposed the AI-empowered architecture integrating Task Evaluation Model and Scheduler during the system design stage. <br> (3) Designed and improved the Task Evaluation Model (model selection, training methods) and enhanced the Scheduler’s rule mechanism to ensure stability and efficiency. <br> (4) Designed data structures and built the MongoDB database, defining user data storage and recording mechanisms. <br> (5) Developed core Scheduler functionalities, including task allocation and rest-time distribution. <br> (6) Contributed to backend development and led data preprocessing for model training. <br><br> **2. Self-Reflection** <br> Through this project, I strengthened my leadership, system design, and problem-solving abilities. As team leader, I learned to coordinate development tasks and ensure smooth collaboration. Designing the AI-empowered architecture deepened my understanding of integrating machine learning with rule-based systems. Developing the scheduler and database enhanced my backend engineering and algorithm design skills. Handling data preprocessing and model training improved my analytical thinking and attention to detail. Overall, this experience enriched my technical expertise and teamwork capabilities, preparing me for more complex research and system development challenges in the future. | e1216649@u.nus.edu |
| Zhao Jiahui  | A0329852U  | **1. Contributions** <br> (1) Backend: Implemented the scheduling logic for both fixed and flexible tasks, integrating AI models to predict users’ energy and pressure levels for adaptive and intelligent task arrangement. <br> (2) Frontend: Designed and developed the core interfaces — including the Dashboard, Task Board, Reports, and Energy/Pressure Panel — featuring real-time data visualization and seamless API integration for smooth user interaction. <br><br> **2. Self-Reflection** <br> This project provided me with a comprehensive understanding of how AI can be applied to intelligent scheduling and personal productivity systems. I learned how to connect models with real-time decision-making algorithms and how to design a system that is both technically efficient and user-friendly. Working on both backend logic and frontend interfaces strengthened my full-stack development skills, as well as my ability to integrate models, databases, and APIs seamlessly. <br> I also gained valuable experience in collaborative development, code versioning, and testing. Overall, this project greatly improved my technical, analytical, and problem-solving abilities, and further inspired my passion for developing intelligent systems. | e1554179@u.nus.edu |



## **SECTION 4: VIDEO OF SYSTEM & USE CASE DEMO**

Refer to `Video/Intelligent_Reasoning_Systems-2025_09-AIS07FT-Group10-AI_Powered_Scheduling_System.mp4` or the youtube link https://youtu.be/1vLSfvlffZw. 



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

**Content** of the report: 

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

<img src="/ProjectReport/Project_Report LaTeX/Images/System/ai_scheduling/aft_scheduling.jpeg" alt="Dashboard">


<hr>
<img src="ProjectReport/Project_Report LaTeX/Images/Logos/nus.png" alt="Cover">
<img src="ProjectReport/Project_Report LaTeX/Images/Logos/iss.png" alt="Cover">
