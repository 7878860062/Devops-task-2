
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



<img width="960" alt="j11" src="https://user-images.githubusercontent.com/48556545/85121193-fb7b4680-b241-11ea-8832-32632c8f4323.PNG">


# Job1 : Pull  the Github repo automatically when some developers push repo to Github.

<img width="960" alt="job1" src="https://user-images.githubusercontent.com/48556545/85121053-c4a53080-b241-11ea-8542-73c55992173a.PNG">

<img width="960" alt="job12" src="https://user-images.githubusercontent.com/48556545/85121099-d555a680-b241-11ea-88db-6998f9e4504a.PNG">

<img width="960" alt="j13" src="https://user-images.githubusercontent.com/48556545/85121123-df77a500-b241-11ea-9cba-878b624df489.PNG">

# Job2 : By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code ( eg. If code is of  PHP, then Jenkins should start the container that has PHP already installed ).

<img width="960" alt="job21" src="https://user-images.githubusercontent.com/48556545/85121157-e9010d00-b241-11ea-9a2e-c89e5edc51a2.PNG">



