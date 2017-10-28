
Steps for Installing OpenCV in Ubuntu 16.04
-
    # apt update
    # apt install sudo
    
    $ sudo apt install python-pip python-dev python-setuptools git cmake python3-pip python3-setuptools wget unzip make
    
    $ sudo apt install build-essential cmake pkg-config libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev  libxvidcore-dev libx264-dev libgtk-3-dev libatlas-base-dev gfortran python2.7-dev python3.5-dev liblapacke-dev checkinstall libpjproject-dev libboost-all-dev libtesseract3 tesseract-ocr gcc-arm-linux-androideabi
    
    $ sudo apt install libpjproject-dev libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libhdf5-serial-dev protobuf-compiler libopenblas-dev emacs dkms synaptic ssh
    
    $ sudo -H pip install --upgrade pip
    $ sudo -H pip install numpy pillow pytesseract require
    
    $ wget -c https://github.com/tech-alchemist/opencv_xenial/raw/master/opencv.3.2.0.zip
    $ wget -c https://github.com/tech-alchemist/opencv_xenial/raw/master/opencv_contrib.3.2.0.zip

    $ unzip opencv.3.2.0.zip ; unzip opencv_contrib.3.2.0.zip
    $ cd opencv-3.2.0/
    $ mkdir build ; cd build

    $ sudo cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D INSTALL_PYTHON_EXAMPLES=ON  -D INSTALL_C_EXAMPLES=OFF -D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib-3.2.0/modules/ -D BUILD_EXAMPLES=ON ..
    $ sudo make -j4         # 4 = Cores of CPU to use during compile # 
    $ sudo make install
    $ sudo ldconfig
    $ sudo rm -f ../../opencv*3.2.0.zip
    
Debug:
-
    $ sudo make clean
    $ sudo make
    
    $ python
    >>> import cv2
    >>>


