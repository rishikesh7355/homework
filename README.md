>>>Task1

*job1*

developer pushes the code to dev or developer branch ,jenkins fetch the code from dev branch and launches a separate dev-docker-environment

*job2*

when code is pushed to master branch jenkins should fetch the code from master branch and launcehes a separate master-docker-environment

*job3*

Quality analysis(QA) team should check whether the website or code is working or not 
if working properly then jenkins  should merge the dev and master  branch and trigger job 2 
