# DEVOPS_TASK-3

## TASK OBJECTIVE:-

`1.` **Create container image that’s has Jenkins installed using Dockerfile Or You can use the Jenkins Server on RHEL 8/7**..

`2.` **When we launch this image, it should automatically starts Jenkins service in the container**..

`3.` **Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins**..

`4.` **`Job-1`** : **Pull the GitHub repo automatically when some developers push repo to Github**..

`5.` **`Job-2`** : 

  *  _**By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top                      of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )**_!!

  *  _**Expose your pod so that testing team could perform the testing on the pod**_!!
  
  *  _**Make the data to remain persistent ( If server collects some data like logs, other user information )**_!!
  
 `6.` **`Job-3`** : **Test your app if it is working or not**.. 
 
 `7.` **`Job-4`** : **if app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer**..


### _PREREQUISITE_:-
                   * RHel-8 * Docker * Gitbash * Github * Jenkins * Kubernetes
                   
---                   

*  _**Created container image that’s has Jenkins installed using Dockerfile or used the Jenkins Server on RHEL 8**_


![Screenshot (138)](https://user-images.githubusercontent.com/64469896/93022896-30acf000-f609-11ea-9a33-14ebf02b70bc.png)

![Screenshot (155)](https://user-images.githubusercontent.com/64469896/93023094-3ce57d00-f60a-11ea-890a-36117b99625a.png)


*  _**JOB-1.** :- _Pull the GitHub repo automatically when some developers push repo to Github_

![Screenshot (156)](https://user-images.githubusercontent.com/64469896/93023897-f561ef80-f60f-11ea-93a7-97171ea20125.png)

![Screenshot (157)](https://user-images.githubusercontent.com/64469896/93023901-001c8480-f610-11ea-86a8-bcfa44533f8f.png)

![Screenshot (158)](https://user-images.githubusercontent.com/64469896/93023914-0a3e8300-f610-11ea-9c8d-568703c90ab4.png)



