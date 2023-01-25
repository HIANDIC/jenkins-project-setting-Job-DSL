# jenkins-project-settings
jenkins-project-settings


Creating Jenkins job with code give us really big flexibility and reusability. **Everything as Code** concept is everywhere now. With help of Jenkins DSL plugin we are able to create configuration file in order to create Jenkins Job.

NOT: Before build the job which is created by using DSL plugin and groovy scripting, we need to do above:

- Appvove the scripting
- Therefore we configure the Jenkins Server:
  . Go to **Manage Jenkins**
  . Go to **In-process Script Approval**
  . Then approve the **Script**
  
- Now we can build our Jenkins Job which we created by using **Jenkins DSL** and **Everything as Code** concept.
