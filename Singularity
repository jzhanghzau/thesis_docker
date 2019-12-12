bootstrap:docker 
From:continuumio/miniconda3

%runscript
    exec echo "haha!"
%post
    apt-get update && apt-get install -y git wget python3-dev python3-pip
    conda install numpy matplotlib scikit-learn 
    conda install -c conda-forge tensorflow
    conda install -c anaconda pandas
    
    
    
    
    
  
