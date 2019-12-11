bootstrap:docker 
From:ubuntu:latest

%runscript
    exec echo "haha!"
%post
    apt-get update 
    apt-get install python3.6 
    apt-get install python3-pip
    apt-get install python3-sklearn python3-sklearn-lib python3-sklearn-doc
    pip install --upgrade pip	
    pip install numpy
    pip install pandas
    pip install tensorflow
    pip install keras
	
    echo "The post section is where you can install, and configure your container."

