1. What are your daily responsibilities as a DevOps engineer?
2. Which DevOps tools are you proficient with?
3. Can you describe the CI/CD workflow in your project?
4. How do you handle the continuous delivery (CD) aspect in your projects?
5. What methods do you use to check for code vulnerabilities?
6. What AWS services are you proficient in?
7. How would you access data in an S3 bucket from Account A when your application is running on an EC2 instance in Account B?
8. How do you provide access to an S3 bucket, and what permissions need to be set on the bucket side?
9. How can Instance 2, with a static IP, communicate with Instance 1, which is in a private subnet and mapped to a multi-AZ load balancer?
10. For an EC2 instance in a private subnet, how can it verify and download required packages from the internet without using a NAT gateway or bastion host? Are there any other AWS services that can facilitate this?
11. What is the typical latency for a load balancer, and if you encounter high latency, what monitoring steps would you take?
12. If your application is hosted in S3 and users are in different geographic locations, how can you reduce latency?
13. Which services can be integrated with a CDN (Content Delivery Network)?
14. How do you dynamically retrieve VPC details from AWS to create an EC2 instance using IaC?
15. How do you manage unmanaged AWS resources in Terraform?
16. How do you pass arguments to a VPC while using the `terraform import` command?
17. What are the prerequisites before importing a VPC in Terraform?
18. If an S3 bucket was created through Terraform but someone manually added a policy to it, how do you handle this situation using IaC?
19. How do you handle credentials for a PHP application accessing MySQL or any other secrets in Docker?
20. What is the command for running container logs?
21. Have you upgraded any Kubernetes clusters?
22. How do you deploy an application in a Kubernetes cluster?
23. How do you communicate with a Jenkins server and a Kubernetes cluster?
24. How do you generate Kubernetes cluster credentials?
25. Do you only update Docker images in Kubernetes, or do you also update replicas, storage levels, and CPU allocation?
26. What types of pipelines are there in Jenkins?
27. Can you define environment variables inside your Jenkins pipeline?
28. What is the role of artifacts in Jenkins, and why do we need to push them to Nexus instead of building and storing them locally?
29. If you’re developing a Python-based application, how do you separate the packages needed for your local deployment to avoid interfering with globally installed packages?
30. How do you handle error handling in Python?

DevOps Interview Questions 
Jenkins
 Git
Linux
Shell Scripting
Ansible
Terraform
Jenkins CICD
Docker
Monitoring
AWS
Kubernetes
SonarQube


============================================================




Questions asked for my devops interview:
Company : centric software 
Day to day life scenario
Architecture of my project , asked to explain outerline of my project
How many clusters you are using for ur prod environment, whats there cpu and ram size
. How you integrate elb , autoscaling
. How you configure vpc
. How to handle disaster recovery
. Asked to explain these git commands  stash,squash,cherry pick
. Explain Dockerfile , how you build simple image
. I said i did internal project as well, he asked me can you give me quick demo , i showed my git and also some screenshots of our frontend 
. How you deploy your application
Interview went for 50min and estimated package was 14 lpa .
. I explained internal project as well in detail
. Related to linux - zombie process,inode,hardlink, kill, how to get process ids ,whats the benifit of root user , what are the other users. (edited) 

==================================================

How do you determine if a subnet is private or public ?
What is diff b\w EBS and EFS
what is the diff b\w ALB and NLB
 if I want to run a specific container in pod in Kubernetes how to run it ?
state in terraform ?
Remote state in terraform ?
what are pipeline stages in your organization ?
terraform data block vs resource block ?
Entry point vs CMD
 what is docker file ?
How the pods are communicating with each other ?
what is vpc endpoint
What are the similarities between SSL and TLS?
What will you do to make you application more secure ?
What is the architecture of your application CICD deployment in current org ?
what is multi stage in docker ?
Namespace in k8 ?
what are tags in ansible ?
what is pod security policy
ami and snapshot difference
Upgrade master node
How will you implement the security for a running container if you find an vulnerability?
What are the various things that can be done to increase Kubernetes security?
Problem faced ?
What is s3 ? (
What are the issue have u faced in Jenkins non prod to prod while building the Jenkins job?
What are issued faced in web application from pre pod to pod ?
Git conflict ?
Branching strategy ?
How often do you release the product ?
What is your role in the project ?
Day to day activities :-
How do you handle issues at the production level ?
pipeline issues in Jenkins
production pipeline issues in Jenkins
Kubernetes issues in production
How do you collaborate with various teams ?
what are the build issues have you faced in your project ?
Deployment strategies ?
What is the architecture of Kubernetes ?
What is booting process in Linux ?
what is inode in Linux ?
What are various plugins in your Jenkins Pipeline ?
How each tool is integrated with Jenkin ( we need to install respective plugin for the same)
how to resolve merge conflicts ?
What is VPC and its components ?
What is difference between NACL and Security groups ?
difference between Network and application load balancer
What are the different dashboards created in Grafana ?
what is ansible playbook ?
What is handlers in Ansible playbook?
What are various modules you have used in Ansible ?
What are Ansible ad hoc command ?
how the pod health check is done in Kubernetes ?
Route 53 types :-
----------------------
helm charts usage ?
terraform modules ?
What is Docker volume and how do you use it?
Network ACL --> to block particular IP
What is the Blue/Green Deployment Pattern?
What is a route table in Amazon VPC?
A role is type IAM identity used to authenticate and authorize to utilize the AWS services.
 policy is nothing but what type of permission is given to the IAM identity
Merge vs rebase
interactive rebase git
squash in git
fast-forward merge in Git?
What is cherry pic
Jenkins error :-
 Provider in terraform
 
 =========================Rahul============
 
What are the services you handled in aws?
 
Do you have any exposer in compute?

Have you created any clusters in eks?

In eks cluster what is meant by managed cluster and non managed clusters?

You have created your cluster in your organization. You created from terraform or manually?

How the kubernetes cluster actually communicate with other services. What are the resources we use?

Difference between HPA and VPA in kubernetes?

Do you have any exposer in helm with kubernetes?

How you are going to connect your master node with your worker node?

How you are discriminating this is a master node and this is a worker node?

What is end points in vpc?

How many ends points we have?

What is vpc peering?

How this vpc peering works?

What are the type of elastic loadbalancers we have?

Difference between ALB and NLB. And which is the best?

What is meant by launch configuration?

What is terraform taint command?

Where you are storing your terraform state file locally or remotely?

If state file was missed what is the next step you will do?

What is the CI/CD you used?

Have you written any declarative pipeline?

What is the difference between declarative pipeline and scripting pipeline in jenkins?

In jenkins what type of pipeline you used?

For multibranch pipeline what are the branching strategy you used?

In jenkins if want to use any secrete as part of your pipeline which cannot be exposed

What is multistaging in docker?

In shell script what is /dev/run ?

If you want to mount the disk what are the steps you followed?,

What is git rebase?

Difference between git rebase and merge?

Do you have any exposer on argoCD?

=====================================================================



How to configure alarm in cloudwatch ??         
How u write terraform file to create ec2 instance ??
What S3 bucket do ??
What  cloud tail does??
How u open log??
How to check the build issues in jenkins??
How u check the error in jenkins pipeline??
. Explain how terraform knows whether it has to update the resource or create a resource.
 Can I overwrite the state log and still apply?
. Difference between tfvars and auto.tfvars ?
. If I want to run any commands after resource creation, How can i do it?
  Answer is Using provisioners
. What are the different types of provisioners and explain where have you used those.
. What if remote-exec command failed in between. What happens to the resources ?
. What happens when we run remote-exec command internally ?
. How do you create multiple resources of the same kind and pack them differently based on the creation order in terraform.
. How do you run terraform in CI-CD ?
. How do you automatically approve and apply changes without prompting for confirmation while executing terraform apply command ?
. What is heap memory. Is it shared between processes ?
. What are the stages in git ?
. How do you undo changes in git ?
. How to check if file is tracked or not ?
. Difference between git revert and git reverse ?
. After commit, how does git revert and git reverse work ?
. I made changes to all 10 files. And I want to commit only 6 files. How to do that?
. I made changes to few files in my repo, locally. I want to switch the branch to some other branch and it is not allowing me to do. Why?
. How does Jenkins connect to its worker nodes?
 Your pipeline is failing with command not found error. How do you troubleshoot it ?
. I had a container running when I run docker yesterday. Today we have run the same. I am not seeing the container. How do you troubleshoot this?
. Too many request errors for a docker container. How do you troubleshoot ?
. How to create a Docker image with no internet connectivity ?
. Any other command which you can use to authenticate yourself to Docker Hub?
. I am unable to access internet inside my container. The host internet is accessible. How do you fix this issue
. The pod is stuck in pending state. How do you troubleshoot it and how do you fix it ?
. what other commands do you run to check a pod's status?
 Explain complete pod lifecycle
 Kubernetes architecture
. What is readiness and liveliness in k8s ?
 What are the two types of Secrets in Kubernetes, and how do they differ?
. Tell me about a time where you are trying to understand a complex problem on your team and you have to dig into details to figure it out
. What kind of data can we gather from Grafana ?
. How do you separate all the infra for TAF, Test, prod...How do you protect them ?
================================================================================================================================================
	==========LINUX ============

1.What is LVM Linux and Why we use LVM.
2.You have /data directory and the space is full and it's mounted on a LVM. How will you resolve this realtime issue.
3.What is the difference mkfs and resize2fs.
4.When you see your pv is failing or faulty than how will you resolve this issue.
5.Can we create a VG directly on a Linux Operating System.
6.How to find a file which starts with ample.Prefix character we don't and we need to list all files in the data directory.
7.What is the basic Difference between du and df command.
8.How to find all the error in log file  with "*.log" extension and we know know the location well. What find command we will run.
9.What is the booting Sequence of a Linux Operating  system.
10.What is the purpose of kernel.
11.What is initrd.
12.What is the PID of init.
13.What is "t" and "T" in sticky bit. why we give sticky bit permission in a file or directory
14. what is w command? what is jcpu and pcpu in  w command.
15.When we mount a directory and we are getting device busy error. How will you you troubleshoot this issue.
16.When I am trying to create a file in /data directory and i am getting permission denied alert. however no space issue and no permission issue. What could be the reason
17.What is inode in linux operating system?
18. In case of softlink inode number is same or different.
19. how to create a soft link in linux operating system.
20. How to roll back a package

===============================================================


Today I appeared for an interview where I got questions on git, docker, kubernetes, terraform and jenkins.
1. What is git rebase?
2. What are the components of a docker file?
3. What is the difference between entrypoint and cmd?
4. What does the add and copy command do? What is the difference between them?
5. How do we implement networking in docker?
6. In Kubernetes, how do you ensure the security of the pods?
7 What is a multistage pipeline in jenkins?
8. How to delete an untagged docker image?
====================================================
1.Migration from onprimes/cloud-to-cloud

2.Disaster recovery strategies and how will you make sure your infra env is completed highly available and reliable . how you will plan 99.99's

3.Steps you will follow to build the application using this below scenerio
frontend application(webapp) + k8s as a backend + Azure sql or amazon RDS including API gateway/LB,networking including issues

4.what are difference b/w adapter service and normal services in k8s

5.how will you mitigate the s3 buckets from vulnerabilities,backup and replication factors

6.zero touch CI/CD automation.

7.Ansible ninja templates,roles,handlers

8.Terraform workspaces,datasources,functions,modules,tfstate file corruption, steps to repair the file. how will migrate the resources from aws to gcp/azure using terrafom.

9.few python or shell automation questions over screen share

10..suppose your script is at public cloud subnet and your bastion/jump host is in private network and your workers nodes were in another private subnet.
steps you will use to bypass the bastion host to connect b/w public and private subnet via jump servers.

=============================================

GitHub commands.

1. 𝗴𝗶𝘁 𝗶𝗻𝗶𝘁: Initializes a new Git repository in the current directory.
2. 𝗴𝗶𝘁 𝗰𝗹𝗼𝗻𝗲 [𝘂𝗿𝗹]: Clones a repository into a new directory.
3. 𝗴𝗶𝘁 𝗮𝗱𝗱 [𝗳𝗶𝗹𝗲]: Adds a file or changes in a file to the staging area.
4. 𝗴𝗶𝘁 𝗰𝗼𝗺𝗺𝗶𝘁 -𝗺 "[𝗺𝗲𝘀𝘀𝗮𝗴𝗲]": Records changes to the repository with a descriptive message.
5. 𝗴𝗶𝘁 𝗽𝘂𝘀𝗵: Uploads local repository content to a remote repository.
6. 𝗴𝗶𝘁 𝗽𝘂𝗹𝗹: Fetches changes from the remote repository and merges them into the local branch.
7. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘁𝘂𝘀: Displays the status of the working directory and staging area.
8. 𝗴𝗶𝘁 𝗯𝗿𝗮𝗻𝗰𝗵: Lists all local branches in the current repository.
9. 𝗴𝗶𝘁 𝗰𝗵𝗲𝗰𝗸𝗼𝘂𝘁 [𝗯𝗿𝗮𝗻𝗰𝗵]: Switches to the specified branch.
10. 𝗴𝗶𝘁 𝗺𝗲𝗿𝗴𝗲 [𝗯𝗿𝗮𝗻𝗰𝗵]: Merges the specified branch's history into the current branch.
11. 𝗴𝗶𝘁 𝗿𝗲𝗺𝗼𝘁𝗲 -𝘃: Lists the remote repositories along with their URLs.
12. 𝗴𝗶𝘁 𝗹𝗼𝗴: Displays commit logs.
13. 𝗴𝗶𝘁 𝗿𝗲𝘀𝗲𝘁 [𝗳𝗶𝗹𝗲]: Unstages the file, but preserves its contents.
14. 𝗴𝗶𝘁 𝗿𝗺 [𝗳𝗶𝗹𝗲]: Deletes the file from the working directory and stages the deletion.
15. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘀𝗵: Temporarily shelves (or stashes) changes that haven't been committed.
16. 𝗴𝗶𝘁 𝘁𝗮𝗴 [𝘁𝗮𝗴𝗻𝗮𝗺𝗲]: Creates a lightweight tag pointing to the current commit.
17. 𝗴𝗶𝘁 𝗳𝗲𝘁𝗰𝗵 [𝗿𝗲𝗺𝗼𝘁𝗲]: Downloads objects and refs from another repository.
18. 𝗴𝗶𝘁 𝗺𝗲𝗿𝗴𝗲 --𝗮𝗯𝗼𝗿𝘁: Aborts the current conflict resolution process, and tries to reconstruct the pre-merge state.
19. 𝗴𝗶𝘁 𝗿𝗲𝗯𝗮𝘀𝗲 [𝗯𝗿𝗮𝗻𝗰𝗵]: Reapplies commits on top of another base tip, often used to integrate changes from one branch onto another cleanly.
20. 𝗴𝗶𝘁 𝗰𝗼𝗻𝗳𝗶𝗴 --𝗴𝗹𝗼𝗯𝗮𝗹 𝘂𝘀𝗲𝗿.𝗻𝗮𝗺𝗲 "[𝗻𝗮𝗺𝗲]" 𝗮𝗻𝗱 𝗴𝗶𝘁 𝗰𝗼𝗻𝗳𝗶𝗴 --𝗴𝗹𝗼𝗯𝗮𝗹 𝘂𝘀𝗲𝗿.𝗲𝗺𝗮𝗶𝗹 "[𝗲𝗺𝗮𝗶𝗹]": Sets the name and email to be used with your commits.
21. 𝗴𝗶𝘁 𝗱𝗶𝗳𝗳: Shows changes between commits, commit and working tree, etc.
22. 𝗴𝗶𝘁 𝗿𝗲𝗺𝗼𝘁𝗲 𝗮𝗱𝗱 [𝗻𝗮𝗺𝗲] [𝘂𝗿𝗹]: Adds a new remote repository.
23. 𝗴𝗶𝘁 𝗿𝗲𝗺𝗼𝘁𝗲 𝗿𝗲𝗺𝗼𝘃𝗲 [𝗻𝗮𝗺𝗲]: Removes a remote repository.
24. 𝗴𝗶𝘁 𝗰𝗵𝗲𝗰𝗸𝗼𝘂𝘁 -𝗯 [𝗯𝗿𝗮𝗻𝗰𝗵]: Creates a new branch and switches to it.
25. 𝗴𝗶𝘁 𝗯𝗿𝗮𝗻𝗰𝗵 -𝗱 [𝗯𝗿𝗮𝗻𝗰𝗵]: Deletes the specified branch.
26. 𝗴𝗶𝘁 𝗽𝘂𝘀𝗵 --𝘁𝗮𝗴𝘀: Pushes all tags to the remote repository.
27. 𝗴𝗶𝘁 𝗰𝗵𝗲𝗿𝗿𝘆-𝗽𝗶𝗰𝗸 [𝗰𝗼𝗺𝗺𝗶𝘁]: Picks a commit from another branch and applies it to the current branch.
28. 𝗴𝗶𝘁 𝗳𝗲𝘁𝗰𝗵 --𝗽𝗿𝘂𝗻𝗲: Prunes remote tracking branches no longer on the remote.
29. 𝗴𝗶𝘁 𝗰𝗹𝗲𝗮𝗻 -𝗱𝗳: Removes untracked files and directories from the working directory.
30. 𝗴𝗶𝘁 𝘀𝘂𝗯𝗺𝗼𝗱𝘂𝗹𝗲 𝘂𝗽𝗱𝗮𝘁𝗲 --𝗶𝗻𝗶𝘁 --𝗿𝗲𝗰𝘂𝗿𝘀𝗶𝘃𝗲: Initializes and updates submodules recursively.

==========================================

Interview Questions for 2.5 to 4 yrs 𝐀𝐖𝐒 𝐰𝐢𝐭𝐡 𝐝𝐞𝐯𝐨𝐩𝐬 𝐫𝐨𝐥𝐞

1. What is GIT stash ?
2. What is a branching strategy?
3. What is the command to discard changes in the working dir?
4. How do you debug the exited container?
5. How do you execute jobs parallely in Jenkins?
6. Maven Lifecycle?
7. How do you upgrade Jenkins?
8. What is called a Parameterised Job in Jenkins?
9. What is called Docker Swarm?
10. How do you handle codes in Nexus satisfactory?
11. How do you manage space issues in the Jenkins server?
12. what is called a multibranch project in the Jenkins server ?
13. How do you secure the Jenkins server?
14. How do you manage GITHUB roles?
15. What is called a NULL resource in Terraform?
16. What is called terraform fmt ?
17. What is called Snowball?
18. How do you manage credentials in Terraform?
19. What is called Code Deploy in AWS?
20. Can you attach a single EBS volume to multiple EC2 instances at the same time?
21. Can you use Multiple FROM in DockerFile ?
22. DockerFile runs as which user?
23. How can we pass an argument to DockerFile?
24. What are deployment strategies?
25. What is called an application load balancer?
26. What is Kubernetes architecture ?
27. What is called Fargate service in AWS?
28. What are Register targets in Ansible?
29. How do you pull artifacts from NEXUS?
30. How to access the S3 bucket privately ?
31. What is the difference between a NAT inst and a NAT Gateway?
32. How can you restrict particular IPs accessing EC2 instances?
33. What is called VPC peering?
34. What is called Transit Gateway?
35. What are the types of autoscaling?
36. To prevent DDOS attacks, which load balancer is used ?
37. What is called a sticky session?
38. What is called Lambda?
39. How do you manage tfstate file in Terraform?
40. How do yo create multiple ec2 instances in terraform ?
41. AWS has released a new service, how does Terraform behave?
42. How do you uncommit the changes that have already been pushed to GitHub?
43. What is the difference between git pull and git fetch?
44. What is called Jenkins File?
45. What is called Shared Libraries in Jenkins?
46. What is called docker networking?
47. What is called a Trust relationship in AWS?
48. What is called Public Subnet and Private Subnet?
49. How do you establish a connection between ec2 instance to another ec2 instance?
50. What is realm command ?
51. How do you differentiate within an AWS account dev env, test env, and prod env?
52. Types of ec2 instances?
53. How can you encrypt the already created unencrypted EBS without creating a fresh EC2 instance?
54. How do you install Nginx in the Ansible playbook?
55. How do you recover the deleted object in S3?
==================================================

devops interview for 2.7 years experience asked below questions:


1. What are the day to day activities?
2. How do you send file from one server to another server
3. Which web server and application server in your project using.
4. How you deploy application in tomact server.
5. What git commands you know.
6. how do you send jar file from server to nexus ?
7. what process you follow to create Jenkins pipeline.
8. How to create ingress.
9. The pods are running successfully but ingress is not working what might be issue explain?
========================================================

1) What are your day to day activities as a DevOps engineer?
2) What kind of automations have you done?
3) Will you support on-call if given an opportunity?
4) Tell some issues you have faced in production and how have you solved?
5) Have you performed RCA of any production issues?
6) Explain the entire process of CICD?
7) Explain some steps where you have mitigated the cost of your applications?
8) Have you enabled any monitoring metrics in your project?
9) Explain the complete architecture of your project?
10) What are the best security measures implemented in your project? 
==============================================================

