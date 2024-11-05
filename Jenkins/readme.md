# Jenkins CICD
## Real interview questions faced during interviews

- What are pipeline stages in your organization?
- What is the architecture of your application CICD deployment in the current organization?
- What is the issue have you faced in Jenkins non-prod to prod while building the Jenkins job?
- Pipeline issues in Jenkins
- Production pipeline issues in Jenkins
- What are the build issues have you faced in your project?
- Deployment strategies
- What are various plugins in your Jenkins Pipeline?
- How do you create a multi-branch Jenkins pipeline?
- How do you upgrade Jenkins?
- What is a shared library?
- What is Jenkins and security tools?
- What is the Jenkinsfile, and how is it used in Jenkins pipelines?
- How to integrate SonarQube in a declarative pipeline?
- How to pass credentials in a pipeline?
- What are the features of Jenkins?
- What is Groovy in Jenkins?
- Which command is used to start Jenkins?
- What are Declarative Pipelines in Jenkins?
- How can you set up a Jenkins job?
- How to create a backup and copy files in Jenkins?
- How can you secure Jenkins?
- What is the use of Backup Plugin in Jenkins? How to use it?


### How to Change the Default Port Number in Jenkins :
1. If Jenkins installed in Linux server, open the file here  : -->  cd /usr/lib/systemd/system/
**** You have to change Environment port ****
2. vim jenkins.service
3. Search for the content "Environment="JENKINS_PORT=8080"
4. Change the port number to your desired number.
5. Execute the commands as follows
6. systemctl daemon-reload
7. systemctl restart jenkins.service
8. Access the jenkins in browser with the new port number