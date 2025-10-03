# maven-project-demo
Learn how to use Jenkins to build a simple Java application using Maven — your first step into CI/CD.

Setup Jenkins Freestyle Job:
Open Jenkins dashboard → New Item → Freestyle project.

Configure Source Code Management.
Push the project to a GitHub repository.
Jenkins can pull code directly from the GitHub repo to automate builds.

Add Build Step → Invoke top-level Maven targets.
Goals: clean install

Save and Build Now.
Verify successful build in console output.

After a successful build:
BUILD SUCCESS
The Java application can be run via Maven or from the generated JAR in target/ folder.






