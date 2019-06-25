################# Header: Define the base system you want to use ################
# Reference of the kind of base you want to use (e.g., docker, debootstrap, shub).
Bootstrap: docker
# Select the docker image you want to use (Here we choose tensorflow)
From: pytorch/pytorch:latest

################# Section: Defining the system #################################
# Commands in the %post section are executed within the container.
% post
        echo "Installing Tools with apt-get"
#        apt-get update
#        apt-get install -y cmake libcupti-dev libyaml-dev wget unzip svn git
#        apt-get clean
#        mkdir /tmp
#        cd /tmp
#        git clone https://github.com/kaldi-asr/kaldi.git
#        cd kaldi/tools
#        ./extras/check_dependencies.sh
#        make
#        echo "Installing things with pip"
#        pip install tqdm
#        echo "Creating mount points"
#        mkdir /dataset
#        mkdir /tmp_log
#        mkdir /final_log


# Environment variables that should be sourced at runtime.
%environment
        # use bash as default shell
        SHELL=/bin/bash
        export SHELL

