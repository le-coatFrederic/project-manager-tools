# Project Manager Tools

## Description 

As an IT project manager, I would like to have an application that will help me doing my job.

I will use my background as Software Engineer and IT Project Manager to build the system that suits me the most.

## Project environment

### Objectives

I wan't to use this tool daily as a project manager. Also, I would like to improve myself by logging everything and tracking all my tasks.

Thus, we can divide the application with multiple systems :

- **Projects managing** : Create, update, delete, and get all the infos of projects. Adding attachments and more.
- **Milestones managing** : Projects can be splitted in differents milestones with their own objectives.
- **Task managing** : In milestones, we can add tasks that will help us developping the project.
- **Time managing** : I will have to record all my actions and get their duration.
- **Schedule managing** : With milestones and task, it will help me schedule my day and week.
- **Journalization** : At the end of days and weeks, I will have to report some data to understand how I worked, what was good and what wasn't.
- **Tracking** : Will help me to understand the evolution of a project.
- **Actors managing** : To know who I'm working with.

### Problem to solve

I have a lot of application that help me doing my job but I don't love them. So, I'm only working on Excel and I always see its limits. 

I wan't to have the simplicity of Excel but the efficiency of multiple project manager tools like time tracker.

## Impacts and project constraint

### My job

I will be the project manager and the developper of this application. Also, I will be the main customer and user.

I'm fully responsible of the success or failure of this project.

### Constraints

- **Money** : this project won't cost a penny except for the server maintenance.
- **Time** : I have a time constraints I fixed myself of 2 weeks developping.
- **Quality** : For now only the back is important and I need to use docker. I will have to create my Dockerfile and be sure it is working well on my server.

## Initialization

In this milestone, I will get all the information I need to buid this project. 

### Needs 

I would like to have an application that help me managing my projects. Thank to it, I will be able to track my work, see where I have some weaknesses and what tasks I will have to do. 

### Modules 

Thanks to the following Use Case Diagram, I will be able to deconstruct the project into different use case.

![dcu_global](/docs/project_init/DCU_Global.jpg)

Then I will detail all the modules : 

- **Manage projects** :

![dcu_project](/docs/project_init/DCU_Project.jpg)

- **Manage milestones** : 

![dcu_milestone](/docs/project_init/DCU_Milestonet.jpg)

- **Manage tasks** : 

![dcu_milestone](/docs/project_init/DCU_Task.jpg)