**Design Documents**


# **Objective**

Give a brief description of the goals of your project.

What questions do you hope to address? What value will you be adding to the space?

We want to program a system that can detect breast cancer with genes. With genes, we can use that to predict breast cancer especially if it's a history thing. Could have a system that detects tumors such as malignant and  benign as an example to detect breast cancer.



---



# **Background**

Describe the background and context for this project.

What is the motivation for studying this topic? What other work has been done: what was good and where does it fall short? If your project is interdisciplinary, give an overview of the key ideas from the connecting disciplines.

Breast cancer is the second most common cancer in American women behind skin cancer. American women have a one- eighth chance of developing breast cancer in their life. Detecting breast cancer using screening techniques can be beneficial to starting treatment while the disease is still in the early stages. This project will create a machine learning model that is able to predict breast cancer using information about the characteristics of tumors. This model will use an algorithm that is capable of comparing a wide range of characteristics of the tumors such as concavity, smoothness, texture and perimeter. The ability to detect breast cancer early leads to more effective methods of prevention and treatment.



---



# **Data Collection**

Describe your preliminary ideas for data collection and cleaning.

Are you planning to use datasets that are already compiled? Will you need to pull supplemental information from additional sources? What plans do you have to clean and prepare your data? How much time are you budgeting for the data collection and cleaning process?

For our data collection process we will use the data that is already available and compiled as well as using resources from other outside sources to gain more insight in terms of how we might use this data to build our model. We will also use supplemental data to bolster our training model to get a good fit for our prediction model when it comes time to test the model and accurately predict whether a patient has breast cancer or not. In order to clean the data, we will check for any missing data or duplicated data, check for outliers, and misspelled words that may throw off our training data for our model. We will take around 3-5 days to complete collecting data as well as cleaning the data to make sure our data is as accurate as possible.

_Note: Students_ frequently underestimate this step. It is important to remind them that sometimes 90 percent of this work is getting the data in a usable format.



---



# **Detail Design/Ideas**

Provide a detailed overview of the project design.

How will you approach the problem? What ideas/experiments do you have planned?



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


Tips:



* Focus on design, not implementation.
* A picture is worth a thousand words. A diagram or drawing of the data and model at times is much easier to understand than words.
* If describing alternatives (e.g., approach, platform, algorithm), explain why it’s not part of your design.
* If you take a different approach than originally designed, come back and update your design docs.



---



# **Project Plan**

Provide a project plan that includes a list of intermediate goals, milestones, and timelines. Also include the schedule of when different team members will take on the program manager and note taker roles.

**Main Goal:** Design a model that can predict breast cancer from characteristics of tumors

**Intermediate Goals:** 

**<span style="text-decoration:underline;">Team Roles</span>**

Chief Executive Project/Senior Code Engineer Specialist Supervisor: Kayla Thames

Administrative Data Analyst: Javon Barret

Code/ Slides Designer Specialist: Xavier Hicks

Chief Executive Editor: 

Virtual Presentation Specialist /Graphics Designer: 

**<span style="text-decoration:underline;">Timeline</span>**

Phase 1: Create Design Document, create project plan

Phase 2: Acquire data, clean/prep dataset, Define and train model, Begin to structure presentation

Phase 3: Use data to test and tune the model, Get feedback on model, Update presentation

Phase 4: Create model predictions, Review results, Make conclusions, Review/Edit presentation, Rehearse Presentation

You will update this project plan throughout the project. It will be a guide that keeps you on track and accountable. It may be helpful to think about the project management session as you create your plan.



---



# **Fairness Considerations**

Complete the ethical storyboarding activity.

You will also complete this again as part of your final project, as it is critical to consider ethical implications early and often throughout any project.

The ethical storyboarding worksheet asks your group to:



* describe a fictional person who was positively affected by a model trained with these data

The system that predicts the range of Sarah’s risk can be determined by the prediction system. Based on the predicted risk values the range of risk will be assigned. When it's predicted, then it can be treated accurately. 



* describe a fictional person who was negatively affected by a model trained with these data

Sarah had other factors of knowing signs of breast cancer, all cancer tests are the potential for diagnosing tumors that will not become life-threatening (overdiagnosis) and the possibility of receiving false-positive test results.



* describe at least two sources of bias the particular model in your story could have

The model story could have bias in the fact that Sarah could have had breast cancer in the past making her more prone to receiving a positive test. Also Sarah could be one that never had cancer and could be tested and receive false positive results.



* describe at least one way you could modify the model to mitigate this bias

In order to mitigate this process we will collect enough data to make sure our model fits the data appropriately, not overfitting the data, to give accurate results in our prediction model.



* describe at least one way you could modify the dataset to mitigate this bias

One way to mitigate this bias in the dataset could be to make sure we create a function to be sure that there is no missing data that could skew our results creating bias.

describe at least one way you could modify the context surrounding the model to mitigate this bias

One way to one way you could modify the context surrounding the model to mitigate this bias could be to make sure we create a function where it be relatable to the person



---



# **References**

Provide an annotated list of reference materials that you used in preparing these design documents, as well as any additional references that you plan to use in your project.

For each reference provide a 1-2 sentence summary of the content and a brief description of how it was (or will be used). 


# 1 Considerations


## 1.1 Assumptions

Since an assumption is a thing that is accepted as true or as certain to happen,the system can detect breast cancer with genes. With genes, we can use that to predict breast cancer especially if it's a history thing. Could have a system that detects lumps as an example to detect breast cancer.


## 1.2 Constraints

With other factors of knowing signs of breast cancer, all cancer tests are the potential for diagnosing tumors that will not become life-threatening (overdiagnosis) and the possibility of receiving false-positive test results. Sometimes age can be a factor in predicting breast cancer.


## 1.3 System Environment

 A system environment according to Microsoft, “defines the properties and methods for determining system and user environment variables.”  When first approaching this problem, we determined a machine learning system as the appropriate system for achieving the project goal.  We determined it based on the assumed user type (doctors), as well as the desired output of the system.  The desired output is predicting patient diagnosis and that signaled to us that a machine learning system would be the best fit for the project.


# 2 Architecture


## 2.1 Overview

A machine learning solution has several clearly defined components. The first is to define a goal. In this project the goal is to determine whether a tumor is malignant or benign in order to predict breast cancer. Once the goal is established data must be acquired or collected.  The data for this project is from the Breast Cancer Wisconsin Dataset which will need to be downloaded and read into the software. Then the data must be cleaned and prepared. The data needs to be transformed into something the algorithm can use to recognize patterns. The data will also be split into a set for training and a set for testing.Then the model will be built. The data must be trained using the training set and then predictions will be made for the test data set. To train the data an algorithm must be applied. In this case a K Nearest Neighbor algorithm is used. Then careful evaluation of how the algorithm responds to the data is conducted.


## 2.2 Component Diagram



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



# 3 Appendices and References
