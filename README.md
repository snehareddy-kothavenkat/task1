# task1

PROBLEM STATEMENT 

The mainstream of the project application will be dealt by the master branch of the task in git VCS( Version Control System ) and any fixes, issues, resolves that have to be inculcated into the mainstream application will be first introduced on the developer branch of the task and when these changes have been successfully deployed, when introduced on the testing environment; they will be merged with the master branch to include into the mainstream application

TASK DESCRIPTION

Job1 :- If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.

Job2 :- If Developer push to master branch then Jenkins will fetch from master and deploy on master-docker environment.
Here, both dev-docker and master-docker environments are on different docker containers.

Job3 :- Manually the QA(Quality Assessment) team will check/test for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger Job2.

DETAILED SOLUTION

https://snehakothavenkat.blogspot.com/2020/07/automate-version-control-systems-to.html
