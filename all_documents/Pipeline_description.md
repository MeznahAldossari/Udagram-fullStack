![pip-diagram drawio (2)](https://user-images.githubusercontent.com/97708390/209306398-7061e290-5c68-460f-a8be-d094cf94df02.png)


## Description

1- User <br>
At the beginning, The Develpoer have to push project into GitHub Repo.<br>

2- GitHub <br>
Before pushing the project, the developer have to create new project in CircleCI and links his GitHub account to CircleCI. Therefore, GitHub connected to CircleCI. So, The GitHub can triggers any changes the pushed by developer.<br>

3- CircleCI <br>
It excuted all instructions that in config.yml. and there are three jobs which are created in CircleCI <br>

- Build <br>
  The enviroment variables are prepared in this step. And install NodeJs then checkout the code. Also, install both frontend and backend parts. At the end, the frontend and backend built in this step. <br>
- hold <br>
  It is waiting until approaval manually before starting to deploy app. <br>

- Deploy. <br>
  The enviroment variables are prepared in this step. And install NodeJs. After that, setting up EB CLI. Then, install aws cli then configure aws access key. And, checkout the code. At the end, deploy, frontend and backend.
