# CloudOps Homework Project

This project is designed to see how candidates solve technical problems and their creativity from a &quot;DevOps&quot; engineer perspective. The take-home assignment is to ask a candidate to provision a .NET Core Application - install and run a web application called &quot;TestWorld&quot; in a cloud environment. The candidate will need to understand how to use various deployment tools and configuration methods to complete the project. You are expected to research, automate, troubleshoot, test, and execute the deployment.  The following information will be provided to help reduce the complexity and time-consumption to each candidate that makes to this interview stage:

- Pick one of the following TestWorld .NET Core 2.0 Standard Standalone application builds
  - Linux
  - Win64
- AWS or Azure Instance (can use your personal one if you want)

Once the project is completed, the candidate will submit the scripts/documentation used to deploy and configure the application. CloudOps will ask the candidate to do a walkthrough of their code and explain their design and approaching to solving the problems. Questions asked by the Team will be technical with focusing on automation, troubleshooting issues, monitoring, and security. At least ten minutes should be allocated for the candidate to ask questions at the end of the session.

# Assignment

## Requirements

1. Deploy the web application &quot;TestWorld&quot; to a free-tier cloud environment
2. Candidate must use their own machine for deployment and development
3. Candidate uses Git to download the project
4. The cloud instance must be a Ubuntu 16.04, Windows Server 2016, or Azure WebApp/Beanstalk
5. Provision the cloud instance, set up security group(s), install packages, configure the app server, and run the application.
6. Provide all documentation and scripts upon completion for review
7. Fully automated in some programming language is a huge PLUS!

Here&#39;s the repo for TestWorld:
 [https://github.com/jamie1911/TestHelloWorld](https://github.com/jamie1911/TestHelloWorld)
 
 ## Minimum Expected Outcome
1. One Server is deployed
2. Security groups allow web traffic to server
3. The server is serving the hello world test .NET Core application site from its public ip/hostname

![Outcome](https://github.com/jamie1911/TestHelloWorld/blob/master/result.PNG)

