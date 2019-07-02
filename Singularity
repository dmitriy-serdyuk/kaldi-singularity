Bootstrap: docker
From: pytorch/pytorch:1.0.1-cuda10.0-cudnn7-runtime

%post
        echo "Installing Tools with apt-get"
        apt-get update
        apt-get install -y cmake libcupti-dev libyaml-dev wget unzip svn git
        apt-get clean
        mkdir /kaldi
        cd /kaldi
        git clone https://github.com/kaldi-asr/kaldi.git
        cd kaldi/tools
        ./extras/check_dependencies.sh
        make

%environment
        SHELL=/bin/bash
        export SHELL

