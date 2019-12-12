bootstrap:docker 
From:ubuntu:latest

%runscript
    exec echo "haha!"
%post
    apt-get update 
    apt-get install -y git wget python3-dev python3-pip
    pip3 install --upgrade pip
    pip3 install numpy
    pip3 install matplotlib
    pip3 install scipy
    pip3 install sklearn
    pip3 install tensorflow
    pip3 install keras
    pip3 install pandas
    echo "The post section is where you can install, and configure your container."

