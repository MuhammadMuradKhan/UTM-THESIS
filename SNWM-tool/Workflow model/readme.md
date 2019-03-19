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

###### **User**

The first component is the user, this component represents the identity that initiates the process of mining data from the social network. Currently it is represented by a user, however, this tool can also be integrated into an existing application framework, where the initiation is done by computer code, rather than a human being. Initiation is done by executing a Java application with additional attributes. These attributes are Social network, URL, Project Title, Timeframe, and the number of posts. Social network attribute can have one out of three options, i.e., Facebook, LinkedIn or Twitter. URL represents the link to the public page (Facebook or LinkedIn) or public handle (Twitter). Project Title is used to create a directory on the computer to store all mined data. Timeframe and number of posts set the scope of the posts. Only those posts will be collected from the social network which resides inside the specified timeframe or is less than the specified number of posts. 


## Phases

![Back-end Roadmap](./images/backend.png)

## Explanation

## References

[1] Schur, M., Roth, A., & Zeller, A. (2015). "Mining workflow models from web applications". IEEE Transactions on Software Engineering, 41(12), 1184-1201.

## Disclaimer
> This tool is developed using open source technologies such as Java, MySQL, and Selenium. Author / GitUser developed this tool for mining public data from the social network websites (e.g. Facebook). Data available on the social network websites is their property and should be used with their permission, however, this tool only mines data that is searchable by Google (anyone can view the public data available on the social networks). This tool is developed for research purposes only and should not be used for financial purposes or to do ill to others. 
