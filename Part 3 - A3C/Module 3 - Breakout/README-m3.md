# artificial-intelligence
 
A3C - env setup >>

1. docker pull pytorch/pytorch
2. docker run -it --name pyt pytorch/pytorch bash

From the container add the conda channel and install required packeges =>
# if on window: conda install pytorch=0.4.1 cuda80 -c pytorch
3. conda config --add channels conda-forge
4. conda install gym gym-box2d gym-classic_control
5. conda install -c menpo ffmpeg
6. conda install -c jiayi_anaconda gym-atari
7. conda install -c conda-forge opencv