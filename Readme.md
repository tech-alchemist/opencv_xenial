

sudo apt update
sudo apt install python-pip python-dev python-setuptools git cmake python3-pip python3-setuptools sudo 

sudo apt install build-essential cmake pkg-config libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev  libxvidcore-dev libx264-dev libgtk-3-dev libatlas-base-dev gfortran python2.7-dev python3.5-dev liblapacke-dev checkinstall libpjproject-dev libboost-all-dev

sudo apt install libpjproject-dev libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libhdf5-serial-dev protobuf-compiler libopenblas-dev emacs dkms synaptic ssh





sudo -H pip install --upgrade pip
sudo -H pip install numpy pillow pytesseract 


mkdir build

cd build

sudo cmake -D CMAKE_BUILD_TYPE=RELEASE \
    -D CMAKE_INSTALL_PREFIX=/usr/local \
    -D INSTALL_PYTHON_EXAMPLES=ON \
    -D INSTALL_C_EXAMPLES=OFF \
    -D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib-3.2.0/modules/ \
    -D BUILD_EXAMPLES=ON ..


make -j4

debug:
make clean
make


sudo make install
sudo ldconfig

###########################3


Server => Ubuntu 16.04

Installing Required Modules For Build


sudo apt-get install build-essential
sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev
sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev

sudo apt-get install build-essential cmake pkg-config
sudo apt-get install libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libxvidcore-dev libx264-dev

sudo apt-get install libgtk-3-dev
sudo apt-get install libatlas-base-dev gfortran libpjproject-dev
sudo apt-get install python2.7-dev python3.5-dev





sudo -H pip install require

cd opencv-3.1.0/
mkdir build
cd build
sudo cmake -D CMAKE_BUILD_TYPE=RELEASE \
    -D CMAKE_INSTALL_PREFIX=/usr/local \
    -D INSTALL_PYTHON_EXAMPLES=ON \
    -D INSTALL_C_EXAMPLES=OFF \
    -D OPENCV_EXTRA_MODULES_PATH=../../opencv_contrib-3.1.0/modules \
    -D PYTHON_EXECUTABLE=/usr/bin/python \
    -D BUILD_EXAMPLES=ON ..


sudo make -j4 

# if Error Then Run:
sudo make clean
sudo make


troubleshoot:

$ python
>>> import cv2




sudo apt-get install build-essential cmake pkg-config
sudo apt-get install libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install libgtk-3-dev
sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libgtk-3-dev
sudo apt-get install libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install build-essential cmake pkg-config
sudo apt-get install libgtk-3-dev
sudo apt-get install libatlas-base-dev gfortran
sudo apt-get install python2.7-dev python3.5-dev
wget -O opencv.zip https://github.com/Itseez/opencv/archive/3.1.0.zip
wget -c -O opencv.zip https://github.com/Itseez/opencv/archive/3.1.0.zip
unzip opencv.zip 

unzip opencv_contrib.zip 




sudo pip install numpy pillow pytesseract argparse logger jinja2 flask werkzeug --upgrade




git clone <link> app


cd appsudo apt-get install liblapacke-dev checkinstall
bash starter.sh




## Installing CPU boosting libs ##
sudo apt-get install libprotobuf-dev libleveldb-dev libsnappy-dev libopencv-dev libhdf5-serial-dev protobuf-compiler
sudo apt-get install libboost-all-dev

sudo apt-get install libatlas-base-dev
sudo apt-get install libopenblas-dev

sudo apt install libpjproject-dev
sudo apt-get install build-essential emacs dkms synaptic ssh




## Build Tesseract ##

sudo apt-get install libleptonica-dev



sudo apt-get install liblapacke-dev checkinstall

