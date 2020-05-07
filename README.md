# jenkinspro
Testing and Production enviroments diffrentialy deployed by jenkins
This project is to deploy different enviroments in docker containers for every branch in a github project.
Whenever any change in a branch is made, then enviroment specific to that branch will deploy that branch.
In our project, we'll have mainly two branches, one is master branch and other is devloper branch.
Master branch will be deployed in production enviroment and developer branch will be deployed in testing enviroment.
For hosting the enviroments, we'll use docker containers. For every enviroment, we'll make a different container in docker that will be totally separated from other enviroment. 
For running the docker containers, we'll use rhel8 that is running on virtual machine on the top of windows 10.
