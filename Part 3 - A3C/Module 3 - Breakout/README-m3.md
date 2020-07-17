# artificial-intelligence
 
A3C - env setup >>

1. docker pull pytorch/pytorch
2. docker run -it --name pyt pytorch/pytorch bash

From the container add the conda channel and install required packeges =>
3. conda config --add channels conda-forge
4. conda install gym gym-atari gym-box2d gym-classic_control
5. conda install -c menpo ffmpeg
6. conda install -c conda-forge opencv