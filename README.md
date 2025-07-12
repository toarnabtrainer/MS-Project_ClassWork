# MS-Project_ClassWork

* **GitHub Link:** https://github.com/toarnabtrainer/MS-Project_ClassWork or https://tinyurl.com/3waatuev
* **MS-Teams Link:** https://tinyurl.com/2s3yxjnr

<hr>

* **Microsoft Project Download, Installation and Activation Free:** https://www.youtube.com/watch?v=lUMPCYinCpM

<hr> 

**PERT - Program Evaluation Review Technique**<br>
**Three-point analysis:**<br>
* **Most Likely Estimate (M)** = Estimate of the most likely value of the duration <br>
* **Optimistic Estimate (O)** = Estimate of the duration under the most favourable conditions <br>
* **Pessimistic Estimate (P)** = Estimate of the duration under the most unfavourable conditions <br>

**PERT = (P + O + 4M) / 6**<br>
**Standard Deviation = (P - O) / 6**<br>
**Variance = Standard Deviation ^ 2**<br>

**PERT Calculations in MS-Project:**
Based on the problem given in the file "Introduction to Project Management.pptx"
* My_O (Number1) Put values in the column manually.<br>
* My_M (Number2) Put values in the column manually.<br>
* My_P (Number3) Put values in the column manually.<br>
* My_PERT (Number4) => ([Number1]+4*[Number2]+[Number3])/6<br>
* My_PERT_Round (Number5) => IIf([Number4]-Int([Number4])>=0.5,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Ceil (Number6) => IIf([Number4]-Int([Number4])>0,Int([Number4])+1,Int([Number4]))<br>
* My_PERT_Floor (Number7) => Int([Number4])<br>
* My_PERT_Variance (Number8) => (([Number3]-[Number1])/6)^2<br>
* My_PERT_StdDev (Number9) => Sqr([Number8])

<hr> 

**Note on BCWS, BCWP and EVM Variables available in following these links:**
* https://tinyurl.com/2s3ctfy2
* https://tinyurl.com/3zbpeapd

<hr>

**These are most followed ways to do resource levelling:**
*	Reduce a task’s duration. <br>
*	Delay a Task. <br>
*	Split a Task. <br>
*	Adjust the resources assigned to a Task. <br>
*	Assign more resources to a Task. <br>
*	Replace an over allocated resource with an under allocated one or remove a resource. <br>
*	Adjust or contour the amount of work assigned to a resource. <br>

<hr>

## Recalculation of the Duration of a Task of types Fixed Units / Fixed Duration / Fixed Work / Effort Driven

![image](https://github.com/user-attachments/assets/1ce8b96c-1376-428b-9f56-4f71f5bb2853)

<hr>

**MS-Project Tips and Tricks:**
* In MS-Project, prorated means that the fixed cost is distributed evenly over the duration of the task. When you track progress, the project incurs the cost of the task at the rate at which the task is completed. For example, if a task has a $100 fixed cost and is 75 percent complete, the project has incurred $75 against that task1.
* In MS Project, we have e-durations (edays, ewks, and emons) and we have the standard days, wks, and mons. edays are understood to be 24 hrs/day with no down time.  
* In Manually scheduled mode in the duration column we can write "Ask your coordinator" for future decision. But not possible in Auto Scheduled mode.
* 


<hr>

**MS-Project Trial Version Download Link:**<br>
https://www.microsoft.com/en-in/microsoft-365/project/compare-microsoft-project-management-software?tab=1&ef_id=_k_Cj0KCQjwy4KqBhD0ARIsAEbCt6gzuZ4E9lm8PhwF34hf5P9GasIDwr5TYhV5oyulunnQVtTydSucYjYaAhnMEALw_wcB_k_&OCID=AIDcmmapr1szny_SEM__k_Cj0KCQjwy4KqBhD0ARIsAEbCt6gzuZ4E9lm8PhwF34hf5P9GasIDwr5TYhV5oyulunnQVtTydSucYjYaAhnMEALw_wcB_k_&gad_source=1&gclid=Cj0KCQjwy4KqBhD0ARIsAEbCt6gzuZ4E9lm8PhwF34hf5P9GasIDwr5TYhV5oyulunnQVtTydSucYjYaAhnMEALw_wcB

<hr>

**MS-Project and Project Management Tutorial Links:**
* **Project 2021 Beginner Tutorial (2 Hours 27 Minutes):** https://www.youtube.com/watch?v=l3ypMRwW9tc
* **Project 2021 Advanced Tutorial (3 Hours 11 inutes):** https://www.youtube.com/watch?v=NnVLgvvkBo8
* **Project 2019 Advanced Tutorial (2 Hours 10 inutes):** https://www.youtube.com/watch?v=xc38Om2HtBA
* **MS-Project 2016 Step by Step Tutorial PDF:** https://tinyurl.com/bdfauhz8
* **MS-Project TutorialsPoint Tutorial PDF:** https://tinyurl.com/5zm6np2t
* **Text Tutorial-1:** https://www.guru99.com/initiation-phase-project-management-life-cycle.html
* **Text Tutorial-2:** https://www.knowledgehut.com/tutorials/project-management
* **Text Tutorial-3:** https://www.projectengineer.net/tutorials/project-management/

<hr>

**MS-Office/O365 Reference Tutorial Links:**
* **MS-Office 2007:** https://edu.gcfglobal.org/en/topics/office2007/
* **MS-Office 2010:** https://edu.gcfglobal.org/en/topics/office2010/
* **MS-Office 2013:** https://edu.gcfglobal.org/en/topics/office2013/
* **MS-Office 2016:** https://edu.gcfglobal.org/en/topics/office2016/
* **MS-Excel Formulas:** https://edu.gcfglobal.org/en/excelformulas/
* **50 Tips to Master Excel ebook:** https://drive.google.com/file/d/0ByEvd0vhZtF3Zm9tY09YNWpuUnM/view
* **How to remove password from an Excel Worksheet:** https://www.youtube.com/watch?v=fsVb6id97_E&list=PLmkaw6oRnRv9uEamCt-PXS-bP-rmoxcLc&index=3
* **MS-Excel Cheat Sheet:**	https://drive.google.com/file/d/1dGDoOiIhFFD71FxUxMO-ZYYE2UYLNGhR/view?usp=sharing

<hr>

## Step by Step Project Plan Preparation:

Planning a project involves several key steps to ensure clarity, organization, and successful execution. Here’s a structured approach to planning a project:

### 1. Define the Project Scope and Objectives
   - **Define the project scope:** Clearly outline what the project will deliver, including deliverables, goals, and outcomes.
   - **Set objectives:** Establish specific, measurable, achievable, relevant, and time-bound (SMART) objectives for the project.

### 2. Identify Stakeholders
   - **Identify key stakeholders:** Determine who will be impacted by the project or who can influence its outcome.

### 3. Conduct Research and Gather Information
   - **Research and gather data:** Collect necessary information to understand the project requirements, constraints, and risks.

### 4. Create a Project Plan
   - **Develop a project plan:** Outline the tasks, timelines, resources, and dependencies required to complete the project.
   - **Define milestones:** Set specific points to evaluate progress and achievement throughout the project timeline.

### 5. Allocate Resources
   - **Identify resources:** Determine the human, financial, and material resources needed for each project task.
   - **Allocate resources:** Assign responsibilities to team members and ensure they have the necessary tools and support.

### 6. Develop a Timeline
   - **Create a project schedule:** Sequence tasks and activities in a logical order.
   - **Set deadlines:** Establish deadlines for each task and milestone to ensure timely completion.

### 7. Risk Assessment and Management
   - **Identify risks:** Anticipate potential obstacles or challenges that could impact the project.
   - **Develop risk management strategies:** Plan how to mitigate or respond to identified risks.

### 8. Communication Plan
   - **Establish communication channels:** Define how information will be shared among team members and stakeholders.
   - **Schedule regular updates:** Determine when and how project progress will be communicated.

### 9. Monitor and Evaluate Progress
   - **Monitor project performance:** Track progress against the project plan and milestones.
   - **Evaluate outcomes:** Assess whether the project is meeting its objectives and make adjustments as needed.

### 10. Document and Review
   - **Document everything:** Keep records of project plans, communications, decisions, and outcomes.
   - **Review and learn:** Conduct post-project reviews to identify lessons learned and areas for improvement.

### 11. Execute the Project Plan
   - **Implement the plan:** Begin executing tasks according to the project schedule and monitor progress closely.

### 12. Closure and Follow-Up
   - **Complete the project:** Ensure all deliverables are finalized and handed over as required.
   - **Conduct project closure:** Evaluate the project’s overall success, archive project documentation, and celebrate achievements.

By following these steps, you can effectively plan and manage a project from start to finish, ensuring it meets its objectives within the specified constraints and delivers value to stakeholders.

---
