Title: Syllabus
Slug: syllabus
Date: 2021-08-18


<style>
pre {
  background-color: #F5F5F5;
  display: block;
  font-family: monospace;
  font-size: 14px;
  white-space: pre;
  border-color: #999999;
  border-width: 1px;
  border-style: solid;
  border-radius: 6px;
  margin: 1em 0;
  padding: 5px;
  white-space: pre-wrap;
}
.containerMain {
    display: flex;
    width: 100%;
    height: 300px;
}
</style>

<br/>
<h5>Welcome to APCOMP 215 / CSCIE-115: Advanced practical data science  </h5>
<br/>

**Course helpline:** [ac215.fall2021@gmail.com](ac215.fall2021@gmail.com)
<hr>

**Instructor:**  Pavlos Protopapas

**Sessions:** Tuesdays and Thursdays -  2:15 PM - 3:30 PM 

**TFs:** Rashmi Banthia,  Shivas Jayaram, Andrew Smith, Gordon Hew

**Office Hours:** TBD

<hr>


<h4>Overview of the Course</h4>

This course aims to review existing Deep Learning flow while applying it to a real-world problem. Then we will build and deploy an application that uses the deep learning model to understand how to productionize models. This course follows the CS109 A/B model of balancing between concept, theory, and implementation.


Split into three parts; the course starts with the review of Deep Learning concepts for data and modeling and how to apply them to different tasks, including vision and language tasks. The next part will be Development, where you use the models you trained in part 1 and incorporate them into real-world applications. Finally, you will Deploy the application in Google Cloud Platform (GCP). The three parts will cover in detail topics such as Transfer learning, Containerization using Docker, and Scaling deployments using Kubernetes.

At the end of this module, you will build efficient deep learning models and design, build and deploy applications that scale.

<h4>Course Topics</h4>

**Project Outline:**

- Introduction to Projects
    - Problem Definition 
    - Proposed Solutions 
    - Project Scope

**Deep Learning:**

- Data
    - Data Pipelines 
    - TensorFlow Data 
    - TensorFlow Records 
    - Dask 
    - Cloud Storage

- Models
    - Computer Vision: Classification 
    - Computer Vision: Segmentation 
    - NLP & Language Models 
    - Transfer Learning and SOTA Models 
    - Distillation and Compression

**Development:**

- Design
    - Virtual Environments, Virtual Machines 
    - Containers & Docker 
    - App Design 

- Develop
    - Setup and Code organization 
    - APIs and Model serving 
    - App frontend

**Operations:**

- Deployment, Scaling, & Automation
    - Google Cloud Platform (GCP) 
    - Kubernetes 
    - Ansible


<h4> Prerequisites </h4>

Your are expected to know the following: 

- Good working knowledge of python 
- Good understanding on the `Tensorflow` Deep Learning framework 
- Basic shell commands 

<h4> Programming:</h4>

- Experience with Python: Functions, Classes, Modules, NumPy, Pandas, Tensorflow
- Basic Data Structures: Dictionaries and Lists 
- File I/O

<h4> Grading Breakdown </h4>

- Discussion Forum 10% 
- Quiz 10% 
- Exercises 20% 
- Milestone 1 5% 
- Milestone 2 15% 
- Milestone 3 15% 
- Final Presentation & Deliverable 25%

<h4>Course Components</h4>

The course includes the following every week:

- 2 Sessions (Lecture+Lab)
- Office hours

**Session**

Before the session begins, students are expected to complete a pre-class reading assignment and and attempt a quiz based on the same. The session will be one and half hours and will have the following layout:


- Sessions will help students develop the intuition for the core concepts, provide the necessary mathematical background, and provide guidance on technical details. 
- Sessions will be accompanied by relevant examples to clarify key concepts and techniques.
- More detailed examples of the topics will be covered in lab the following day

Students must participate in sessions.  

**Lab**
The lab is a one and half hour session divided into 3 parts:

- Quiz and Q&A Session: Q&A and go over any quiz related topic from sessions
- Tutorial: This will be an instructor driven in-depth implementation walk through of code related to the topics covered in the previous session. These tutorials will help you understand the concepts and give you starter code that will help in your projects
- Homework Discussion: Code that cannot be completed in tutorials will be left as an exercise for the student to complete as homework. We will go over hints to complete your homework which will be an individual effort.

It is encouraged to be present in the lab as most of the homework can be done during this time. 

**Reading Assignments**

The course schedule may include readings which will be available before the lecture. The goal of the reading assignments is to prepare for class, to familiarize yourself with new terminology and definitions, and to determine which part of the subject needs more attention.

Each session may have a short quiz at the beginning which covers the assigned reading for that week.

**Homework**

As mentioned above, post each lab there will be parts of the tutorial that will need to be completed as homework. 

**Project**

During the entire course you will work in teams and implement a project. The various topics in the class are designed to help you build milestones in an incremental fashion and build towards the end goal. The final outcome with your project will be a fully working AI App.


- Project groups need to be formed by the first week of class
- Group size : 4
- Select a project from the list given or bring your own
- Criteria for projects are:
    - Deep learning task implemented should include both computer vision and language models
    - The end product should be a deployable app that uses the models in the backend in some form

- If you plan to bring your own project idea, the following additional criteria must be met:
    - Dataset size 5 Gigabytes or larger
    - Data should include images and text

Please find a more detailed summary of all projects here. [TODO]

<h4>Deadlines</h4>

- All quizzes are due before the day the next session.
- All homework are due before the day the next lab. 
- There will be no extensions given for the homework and quizzes.
- The deadline for the project milestones will be announced in the scaffold.

<h4>Software</h4>
All softwares required for this course and installation instructions/help will be provided in Lab 1

<h4>Course Policies</h4>

**Getting Help**

For questions about homework, course content, package installation, after you have tried to troubleshoot yourselves, the process to get help is:

- Post the question on ED and hopefully, your peers will answer. Note that questions on ED are visible to everyone. The teaching staff monitors the posts.
- Attend Office Hours, this is the best way to get help.
- For private matters send an email to the instructor.

**Academic Honesty**

Ethical behavior is an important trait, from ethically handling data to the attribution of code and work of others. Thus, in this session, we give a strong emphasis on Academic Honesty.

As a student, your best guidelines are to be reasonable and fair. We encourage teamwork for problem sets, but you should not split the homework and you should work on all the problems together.

We have included some ideas below of acceptable and not acceptable behaviors. Engaging in not acceptable behavior regarding academic honesty will be handled accordingly.

Please be responsible and when in doubt ask the course instructors.

**ACCEPTABLE:**

- Discussing materials and engaging in OH.
- Helping debug.
- Using a few lines of code found online or another forum as long as you cite the origin and attribute authorship of code.
- Searching online to expand your knowledge and for debugging
- Using a tutor, provided the tutor does not do your work for you.

**NOT ACCEPTABLE:**

- Accessing a solution to some problem prior to submitting your own.
- Failing to cite the origins of code or techniques that you discover outside of the course’s own lessons and integrate into your own work.
- Paying or offering to pay an individual for work that you may submit as your own.
- Providing or making available solutions to problem sets to individuals who might take this course in the future.
- Searching for or soliciting outright solutions to problem sets online or elsewhere.


**Academic Honesty**

Ethical behavior is an important trait of a Data Scientist, from ethically handling data to attribution of code and work of others. Thus, in AC295 we give a strong emphasis to Academic Honesty. As a student your best guidelines are to be reasonable and fair. We encourage teamwork for problem sets, but you should not split the assignments and you should work on all the problems together.

**Accommodations for students with disabilities**

Students needing academic adjustments or accommodations because of a documented disability must present their Faculty Letter from the [Accessible Education Office](http://www.aeo.fas.harvard.edu/)(AEO) and speak with Pavlos by the end of the third week of the term: Friday, September 18[TODO].  Failure to do so may result in us being unable to respond in a timely manner. All discussions will remain confidential.

**Accommodations for students with disabilities**