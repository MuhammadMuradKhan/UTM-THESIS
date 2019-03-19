<p align="center">
  <a href="https://github.com/MuhammadMuradKhan/UTM-THESIS/tree/master/SWM">
    <img src="https://raw.githubusercontent.com/MuhammadMuradKhan/iconspack/master/github.png" alt="Git repo" width="96" height="96">
  </a>
  <a href="https://www.researchgate.net/project/Tool-Social-Network-Web-Mining-SNWM">
    <img src="https://raw.githubusercontent.com/MuhammadMuradKhan/iconspack/master/rg.png" alt="Research material"  height="96">
  </a>
  <p align="center">
<a href="mailto:muradtariq.tk@gmail.com?Subject=Question%20regarding%20SNWM%20Tool"><img src="https://img.shields.io/badge/feedback-@MuhammadMuradKhan-blue.svg" /></a>
  </p>

  <h2 align="center">Social Network Web Mining (SNWM) Tool workflow model</h2>
 

## Introduction

This section presents the workflow model of the SNWM tool. SNWM workflow model is partitioned with respect to components and phases. The workflow is divided into four components and six phases. This workflow model is inspired by the model presented by Matthias Schur [1].

![Web Developer Roadmap Introduction](./workflow.jpg)

## Components 

There are four components of the workflow model. 

###### User

The first component is the user, this component represents the identity that initiates the process of mining data from the social network. Currently it is represented by a user, however, this tool can also be integrated into an existing application framework, where the initiation is done by computer code, rather than a human being. Initiation is done by executing a Java application with additional attributes. These attributes are Social network, URL, Project Title, Timeframe, and the number of posts. Social network attribute can have one out of three options, i.e., Facebook, LinkedIn or Twitter. URL represents the link to the public page (Facebook or LinkedIn) or public handle (Twitter). Project Title is used to create a directory on the computer to store all mined data. Timeframe and number of posts set the scope of the posts. Only those posts will be collected from the social network which resides inside the specified timeframe or is less than the specified number of posts. 

###### Selenium

The second component is the selenium. The simplest way to understand this component is to imagine a browser that can be controlled using programmable commands. Selenium usage is divided into three parts, Selenium web driver, a Browser and Jave libraries. Selenium web driver is a standalone software that acts as a server. Selenium web driver is configured to launch a Browser (second part) and control all interactions performed on the browser. Selenium web driver is initiated using java code via Selenium libraries. Once selenium libraries are initiated, java code is written to send commands to the driver, which in response perform actions on the browser and return the state of the web to the java application. 

###### Java agents

The third component is the Java agents. Java agents is a Java program which mimics human behavior on the social network website, hence, it is called an agent [2]. This component is further divided into human similar actions such as LoginToFacebook(), GetPosts(), GetPostsAttributes(), GetPostsComments() and GetPostsLikes(). Each action is represented by a function that performs respective tasks on the browser connected via selenium web driver.

###### MySQL Database

The fourth component of the model is the MySQL database. This component is responsible for storing information extracted from the mined data. Selenium and Java agents work with HTML code retrieved from the social network websites, whereas, for each HTML code, java agent extracts the valuable information such as Post's ID, Post's Message, Post's Likes count, Post's Comments count. Also for each post user who provided the likes and comments are also extracted. A user is identified by the unique link at the Facebook website. This link is available at any place a user provides a comment or like. All of this information is stored inside the Database for research purposes.

## Phases


## Explanation

## References

[1] Schur, Matthias, Andreas Roth, and Andreas Zeller. "Mining workflow models from web applications." IEEE Transactions on Software Engineering 41, no. 12 (2015): 1184-1201.

[2] Nwana, Hyacinth S. "Software agents: An overview." The knowledge engineering review 11, no. 3 (1996): 205-244.

## Disclaimer
> This tool is developed using open source technologies such as Java, MySQL, and Selenium. Author / GitUser developed this tool for mining public data from the social network websites (e.g. Facebook). Data available on the social network websites is their property and should be used with their permission, however, this tool only mines data that is searchable by Google (anyone can view the public data available on the social networks). This tool is developed for research purposes only and should not be used for financial purposes or to do ill to others. 
