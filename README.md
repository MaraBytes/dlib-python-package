# dlib-python-package
This is a manual installation guide for those who have problems installing dlib in python windows. 

# WINDOWS
1. Download this repo and got to file location
2. Navigate to the project repo and open cmd in there.
3. While in the project folder via cmd type ```pip install dlib-19.19.0-cp38-cp38-win_amd64.whl```
4. That's it dlib will be succesfully installed
# Screenshot
<img src="https://github.com/Oyopiz/dlib-python-package/blob/master/scrn/notme.png" alt="Your image title" width="550"/>
![alt text](https://github.com/Oyopiz/dlib-python-package/blob/master/scrn/notme.png)
# UBUNTU
 *1)* Assign root permission and update ubuntu first

 sudo su

 apt-get update


 *2)* Check your version & path for python & pip.

 which python3



 python3 -V



 which pip3



 pip3 -V


 *3)*

 pip3 install cmake


 *4)*

 apt-get install -y --fix-missing \

     build-essential \

     cmake \

     gfortran \

     git \

     wget \

     curl \

     grapgicsmagick \

     libgraphicsmagic-dev \

     libatlas-dev \

     libavcodec-dev \

     libavformat-dev \

     libgtk2.0-dev \

     libjpeg-dev \

     liblapack-dev \

     libswscale-dev \

     pkg-config \

     software-properties-common \

     zip


 *6)*

 apt-get install python3-dev


 *5)*

 pip3 install dlib


 ------------------------------

 ✅ Done
