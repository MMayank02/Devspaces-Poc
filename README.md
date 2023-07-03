# AIInt-poc



## Getting started

### python-hello-world

A simple program that displays “Hello, World!”. It's often used to illustrate the syntax of the language.

### devfile.yaml

Devfile to configure the devworkspace

### extensions.json

Extensions for Gitlab workflow, Python and chatgpt


## License
For open source projects, say how it is licensed.

## Project status
POC in progress


1. Open Backstage and Gitlab Project
2. Go to component section
3. Create a component using Template
4. Add in parameters (Pre-req - Link to Gitlab Repo in Readme)
5. Shift the cursor to Gitlab - Show the various files in Gitlab
6. Show Workspace topology that no devspace or any other infra is running
7. Come back to backstage, open the link to Devspace (need to check how to trim time for Devsoace creation)
8. Show Workspace topology that devspace other infra is running
9. Open Ide terminal to show - git remote show origin - This will point to Gitlab
10. Open Extensions tab to show that all extensions were added to the IDE
11. Choose CodeGpt and add the API key (Trim the copy of API key part)
12. Run code suggestions - What is codegpt - show answer
13. Run code suggestions - have syntax error in line# - Ask code GPT for fix
14. Make the changes in the code
15. Now run Devfile task to spin the runner (Trim the time it takes)
16. Now go to the dashboard to show that Helm runner is registered
17. Go to GItlab and show that inner is registered to the project created
18. Commit the changes in the IDE
19. Switch to Gitlab
20. Show pipeline triggered in Gitlab
21. Show CI/CD to showcase that pipeline is running and jobs status
22. Finally show the Wiki Dashboard
