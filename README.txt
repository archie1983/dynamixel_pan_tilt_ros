Building this required re-installing Eigen3 because it seemed to have no inlude files:

sudo apt install --reinstall libeigen3-dev

Other suggestions were to tell cmake where is Eigen3, but that still failed during linking:

sudo cp /mnt/storage/florence/cartographer_ws/src/cartographer/cmake/modules/FindEigen3.cmake /usr/share/cmake-3.16/Modules/
