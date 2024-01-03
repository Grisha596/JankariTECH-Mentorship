# CI

- Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project.

# Github Actions

- GitHub Actions is a feature on the GitHub platform that allows you to automate workflows for your software projects. With GitHub Actions, you can define custom workflows to build, test, package, release, and deploy your code directly from your GitHub repository.
- [Details](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)

- Here are some key concepts related to GitHub Actions:

1. Workflow: A workflow is a series of steps that are executed automatically in response to certain events, such as pushing code to a repository, creating a pull request, or releasing a new version. Workflows are defined using YAML files that reside in the .github/workflows directory in your repository.

2. Event: An event is a specific activity that triggers a workflow to run. Examples of events include push (code is pushed to the repository), pull_request (a pull request is opened or updated), and schedule (a workflow is triggered on a scheduled basis).

3. Job: A job is a set of steps that run on the same runner (execution environment). A workflow can consist of one or more jobs that run in parallel or sequentially.

4. Step: A step is an individual task in a job. Steps can include actions, which are reusable units of code that perform specific tasks. Actions can be provided by the GitHub community or created by you.

5. Action: An action is a reusable unit of code that can be used in different workflows. Actions can be written in various programming languages and can be shared on the GitHub Marketplace or within your repository.

6. Runner: A runner is the environment in which jobs are executed. GitHub provides hosted runners with various operating systems, or you can use self-hosted runners on your own infrastructure.

- For example, you can set it up so that whenever you add new code to your project, the robot automatically checks if everything is working correctly by running tests. If all is good, it can even deploy your software to a server.

This automation saves your time and ensures that important steps in your development process happen consistently without manual effort.