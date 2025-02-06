# FAST-LIVO2 with mid360
- noetic
- opencv4.2
- eigen3.3.4
- PCL>=1.6
- Sophus 
```bash
git clone https://github.com/strasdat/Sophus.git
cd Sophus
git checkout a621ff
mkdir build && cd build && cmake ..
make
sudo make install
```
## how to use
```bash
cd FAST-LIVO2
catkin_make
source devel/setup.sh
roslaunch fast-livo mapping_mid360.launch
```
