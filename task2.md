
![OIPAWXKTNXV](https://user-images.githubusercontent.com/48556545/85120995-a9d2bc00-b241-11ea-952e-8483956a57f4.jpg)

## Devops task 2
1. Create container image that’s has Jenkins installed  using dockerfile 

2. When we launch this image, it should automatically starts Jenkins service in the container.

3. Create a job chain of job1, job2, job3 and  job4 using build pipeline plugin in Jenkins 

4.  Job1 : Pull  the Github repo automatically when some developers push repo to Github.

5.  Job2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of  PHP, then Jenkins should start the container that has PHP already installed ).

6. Job3 : Test your app if it  is working or not.

7. Job4 : if app is not working , then send email to developer with error messages.

8. Create One extra job job5 for monitor : If container where app is running. fails due to any reson then this job should automatically start the container again.

## Screenshot 

# cmd for creating docker file
<img width="673" alt="creatingdf" src="https://user-images.githubusercontent.com/48556545/85122994-1602ef00-b245-11ea-97a0-df72ff732643.PNG">

<img width="960" alt="j11" src="https://user-images.githubusercontent.com/48556545/85121193-fb7b4680-b241-11ea-8832-32632c8f4323.PNG">

add email plugin
<img width="960" alt="initial" src="https://user-images.githubusercontent.com/48556545/85135577-ec08f700-b25b-11ea-9ed9-d14dff12cc07.PNG">


# Job1 : Pull  the Github repo automatically when some developers push repo to Github.

<img width="960" alt="job1" src="https://user-images.githubusercontent.com/48556545/85121053-c4a53080-b241-11ea-8542-73c55992173a.PNG">

<img width="960" alt="job12" src="https://user-images.githubusercontent.com/48556545/85121099-d555a680-b241-11ea-88db-6998f9e4504a.PNG">

<img width="960" alt="j13" src="https://user-images.githubusercontent.com/48556545/85121123-df77a500-b241-11ea-9cba-878b624df489.PNG">

# Job2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of  PHP, then Jenkins should start the container that has PHP already installed ).

[ JOB 2 : This job triggers as soon as the JOB1 is built successfully and this job checks the code and respectively launches the respective interpreter, copies the code to that interpreter container and deploys the code to the webserver. ]
<img width="960" alt="j2n" src="https://user-images.githubusercontent.com/48556545/85134207-bebb4980-b259-11ea-87cd-b7fd50baabf9.PNG">

<


# Job3 : Test your app if it  is working or not.
<img width="960" alt="j3" src="https://user-images.githubusercontent.com/48556545/85123043-26b36500-b245-11ea-8390-0fbdc177f7c8.PNG">

<img width="960" alt="job 32" src="https://user-images.githubusercontent.com/48556545/85123076-2fa43680-b245-11ea-8c9c-615fb913365d.PNG">




# JOB4 : After all the above mentioned jobs are run successfully then this job triggers and keeps on checking whether the interpreter container is running and if in case the container stops it starts the container again. Finally it acts as a monitoring job to monitor the interpreter container.
<img width="960" alt="jb4" src="https://user-images.githubusercontent.com/48556545/85134236-cda1fc00-b259-11ea-87f0-1ea313fbef67.PNG">
 last image
 
 With all the jobs successfully run and no errors in the code , the port 80 of my apache webserver shows this output which is the php code in my github:

<img width="960" alt="html" src="https://user-images.githubusercontent.com/48556545/85134230-cb3fa200-b259-11ea-96f4-23e2f6a64deb.PNG">


# Thanku for  reading/check this

