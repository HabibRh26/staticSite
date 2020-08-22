---
title: "GitHub For Babies"
date: 2020-06-08T06:15:40+06:00
hero: /images/posts/GitHub_posts/post1/git-cover.jpg
menu:
  sidebar:
    name: GitHub Part--1
    identifier: GitHub-post-1
    parent: GitHub
    weight: 30
---

You Perhaps heard the name of **GitHub** but haven't had the occassion to dive deep into it, Right? Then I must say you in the right place.
The intention of this post is to make you understand **Git**,**GitHub** and its mechanism like you are a grade 5 student. Warning! If you want to be an expert then I would say you are in wrong place. Let’s start!
<!--more-->

<!-- ![img1](/images/posts/GitHub_posts/post1/img1.jpeg)  -->



Imagine a team of 3 members are given a group assignment to complete collaboratively by their course instructor. What do you think? How should they proceed? Suppose, the members are Leo, Raj and Sheldon. Now, what these members can do is divide their tasks among them and sit in front of their own computer and start coding. After finishing their own tasks they can use a flash drive to cut and paste individual contribution to form a fresh main project which they will submit to their instructor. Right?

### Let’s do some case study-
**Case-1:** </br>
What if there occurs a fault in the coding of Raj just 20 minutes before the deadline and Raj is in relative’s home, who is gonna solve the issue in absence of Raj? Even Raj can solve the issue as he has laptop with him but it will take more than 1 hour to come, solve the issue and then to do those cut, paste, replace stuffs in the main project. But they have got 20 mins.Do they have any solution? </br>
**Case-2:** </br>
Imagine Raj has the design tasks to do. He implemented a layout and showed to his team mates but they told him to change the layout by 30%. Then he changed and implemented accordingly. After some time,his team mates told him that they are finding it difficult to match the back-end coding of this layout design. So it would be convenient for them if they switch back to the previous version of the layout design. Alas! They have got no back up of the previous version. </br>
**Case-3:** </br>
What if it is an one man show? I mean if the entire project is done by Sheldon how can the course teacher verify?
What if they have internship opportunity,how can they show the team work they did in the undergrad life?Should they carry pen drive to all job interview? </br>
**Version Control System** is A good solution for all the above mentioned cases.In fact, there are tons of reasons and advantages to use VCS(Version Control System). For the sake of simplicity we just mentioned some cases that can entice you to understand why you need to use VCS considering you are an absolute beginner.
### Types of VCS

There are various types of VCS-
* Github
* Bitbucket
* GitLab </br>
In this series of post we will try to learn the basic concepts and usage of git and GitHub.
Where GitHub is a VCS git is a command line tool used for GitHub.Using the CLI(Command Line Interface) of git we interact with GitHub which is an online storehouse of our projects. </br>
### Diving Deep into Some Real Stuffs
To work with GitHub,we need to first install git. As it is a platform independent tool and there are some good tutorials on YouTube about installing git in your machine,we will not go into this in this article. </br>
To begin with,we have to first create a GitHub account through this link. Then we need to create a repository by clicking the “+” icon in the top right corner of the link.After clicking the icon,we will select the first item from the drop down that is “New Repository”. During the creation of the repository,we need to mark the checkbox called “Initialize this repository with a README”. We will discuss later what this README is and how to use it.
</br>
</br>
</br>
 > ![img2](/images/posts/GitHub_posts/post1/img2.png) 
</br>
</br>
</br>
### Cloning an Existing Repository
The first thing we need to understand is Clone.Clone refers to downloading a repository from GitHub. After the creation and initialization of the repository now we have to download the repository. For this, we can make a new folder or navigate to a folder. Then we have to open the terminal. For windows right click and find an option “open with git bash “ for Linux just open the terminal pressing ctrl + shift + T. When you have opened the terminal now you have to clone or download a repository. In order to perform this,you have to go to your GitHub acc where you created your repository. In the repository,go to the right side and click the green button named ‘clone or download” then you will find a URL link of your repo.

</br>

 > ![img2](/images/posts/GitHub_posts/post1/img3.png) 

</br>

For now,just copy the URL and then come back to the terminal of your computer. In the terminal type the following command to download or clone the repository. </br>

``git clone https://github.com/Name500/project_Multimedia.git``

where ``https://github.com/Name500/project_Multimedia.git`` is the link that we copied from GitHub.
</br>
When the download finished if you go inside the folder you will see that you have successfully downloaded the repository which you created in GitHub site with a readme file and a git folder.
</br>

> ![img2](/images/posts/GitHub_posts/post1/img4_1.png) 

</br>

If you are in windows and the [hidden file view](https://bit.ly/3iOmxN7) option is enabled then you will see that inside the repository there is a folder named .git which contains all the records of your file history. For linux press ctrl+H to view this folder.
As we cloned the repo and (say)are in the Directory where we cloned the repository. Now go to the terminal and perform the following command-
</br>

`git status`

You will have a window like below says working tree clean:
</br>

> ![img2](/images/posts/GitHub_posts/post1/img4.png) 

</br>

That's all for Today. Thanks for being with me. You can head over to [Part 2 of this series](https://www.habib25cseju.me/posts/github/github_for_babies_2/)
</br>
**P.S**- Cover Image credit goes to [Unsplash](https://unsplash.com/)




