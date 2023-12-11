# K6_GitHubActions
Repository with K6 projects to be executed at GitHubActions


### **K6 Installation**
- K6 Documentation: https://grafana.com/docs/k6/latest/get-started/installation/

### 📂**Project structure in Visual Studio Code**
![image](https://github.com/almeidas-tatiane/K6_GitHubActions/assets/68197687/11f27ca3-8d8e-432f-9705-25521f331e62)

- In the .github\workflows folder, you'll find the load-test.yml. This file contains the action to be executed at GitHub;
- The GitHub Action will execute the file everytime a push command is used;
- In the src\requests folder, you'll find the performance test file that the yml file will use in the GitHubAction.

### **Steps to execute the yml file at GitHubActions**
- Do any change in the performance test script;
- Do a git add, git commit and git push;
- After the git push, go to GitHub, click in the K6_GitHubActions repository, and click on Actions tab;
- You'll see a workflow in progress.

