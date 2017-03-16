Bootstrap: docker
From: ubuntu:latest

%runscript

    echo "You are running my ubuntu singularity container!"
    exec echo "Hello you!" "$@"

%post
 
   echo "Here we are installing software and other dependencies for the container!"
   apt-get update
   apt-get install -y git 
