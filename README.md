# demo-app: Jenkins Pipeline Example

A minimal Java 17 Maven project for learning a Jenkins Declarative Pipeline.

## Files
- `pom.xml`: Maven project configuration and JUnit test dependency.
- `Jenkinsfile`: Pipeline with Clone, Build, and Test stages.
- `src/main/java/com/example/App.java`: Simple Java program.
- `src/test/java/com/example/AppTest.java`: Automated test.

## Before running Jenkins
1. Create a GitHub repository named `demo-app`.
2. Replace `YOUR_USERNAME` in `Jenkinsfile` with your GitHub username.
3. Commit and push all project files to GitHub.
4. Configure a Jenkins Pipeline job to use this repository.
5. Ensure the Jenkins agent has Java 17, Maven, and Git installed.

This Jenkinsfile uses `bat`, appropriate for a Windows Jenkins agent. If the Jenkins agent runs Linux, change `bat` to `sh`.

## Run locally
From this folder, run:
```powershell
mvn clean test
```
