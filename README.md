# Skills2022v2 - Nikolai Vorotnev
## Task 1
### GitHub Skills Test
### Task preparation
To do this task I prepared my github account and created a directory in DEVASC-LABVM
### Task implementation
Firstly, I created new github repository, then created new SSH connection for DEVASC-LABVM, and finally cloned repository to the machine.
And the last step - I renamed repository from "Skills2022" to "Skills2022v2" in GitHub web interface.
### Task troubleshooting
Where is no troubles with completing this task
### Task verification
![Task1_1](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task1_1.png)
## Task 2
### Ansible Skills Test
### Task preparation
To complete this task I prepared an ansible and VS code on the machine
### Task implementation
Firstry, I enabled ssh server on DEVASC-LABVM. Then I opened /labs/devnet-src/ansible folder in VS Code and started to configure parameters.
I specified one web server in hosts file, and added parameters in ansible.cfg file.
After it I created playbook file with name test_apache_playbook.yaml, in which I added information to install and test webservers with a ping command.
Filanny, this playbook was runned successfully.
All related files is in Task 2 folder in this repository.
### Task troubleshooting
It was important to write yaml file properly, because every space is significant in this file.
### Task verification
![Task2_1](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_1.png)
![Task2_2](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_2.png)
![Task2_3](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_3.png)
![Task2_4](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_4.png)
![Task2_5](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_5.png)
![Task2_6](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_6.png)
![Task2_7](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_7.png)
![Task2_8](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task2_8.png)
## Task 3
### Docker
### Task preparation
In this task a docker package was used
### Task implementation
The first step is to go to the Dockerhub website. (Screenshot 1). Here we need to search for Alpine server. Let's find and install it (Screenshoot 2 and Screenshoot 3).
Finally, let's test our progress by "docker run alpine" command to make sure that everything works properly. As we can see, there is no error messages, so task is done successfully (Screenshot 4).
### Task troubleshooting
It's important to use sudo with a lot of docker commands because root is required for it.
### Task verification
![Task3_1](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task3_1.png)
![Task3_2](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task3_2.png)
![Task3_3](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task3_3.png)
![Task3_4](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task3_4.png)
## Task 4
### Jenkins
### Task preparation
To do this task it's necessary to install java first. The second step was to install Jenkins
### Task implementation
After installing Jenkins, there was a first installation of it.
After this there was a step to install Docker Plugin in Jenkins.
The next step was to create a pipeline and run it.
### Task troubleshooting
On the running step there was a problem: Jenkins didn't recognize "docker" command. Do this command was replaced by "any".
### Task verification
![Task4_1](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_1.png)
![Task4_2](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_2.png)
![Task4_3](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_3.png)
![Task4_4](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_4.png)
![Task4_5](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_5.png)
![Task4_6](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task4_6.png)
## Task 5
### Programming and Unit Testing
### Task preparation
To do this task it's necessary to prepare a text editor and python.
### Task implementation
First of all, let's install a python (Screenshot 1).
We need to write a code for a module. The first task is to write a function that return you the count of unique elements in a given 
numerical list. Let's write it.
You can see the code of a first program on Screenshot 2.

Then we need to write a next program:
Given a list of people objects, create a function that sorts the list by an 
attribute name. The attribute to sort by will be given as a string. 
Notes: Sort the list in ASCENDING order, all objects will be valid.
Let's write a code for it.
You can see a result on a Screenshot 3.
### Task troubleshooting
There was some troubles with a code syntax, but it was resolved in process.
### Task verification
![Task5_1](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task5_1.png)
![Task5_2](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task5_2.png)
![Task5_3](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task5_3.png)
Full code you can find in Task5/module.py
And finally, let's add a unit tests code:
![Task5_4](https://github.com/vrtnev/Skills2022/blob/main/Screenshots/Task5_4.png)
