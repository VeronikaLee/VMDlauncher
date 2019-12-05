# VMDlauncher
ansible script to install and launch VMD 1.9.3 from your Ubuntu
https://quarter-prince.()/vmd-1.9.3.bin.LINUXAMD64-CUDA8-OptiX4-OSPRay111p1.opengl.tar.gz - be sure I am online

tar -zxvf vmd-1.9.3.bin.LINUXAMD64-CUDA8-OptiX4-OSPRay111p1.opengl.tar.gz
This will extract the folder to your downloads folder. You can then just

cd vmd-1.9.3

./configure LINUXAMD64

cd src

sudo make install (install cmake first)

install x-server from install software
add Virtual Box to .codio file(added automatically)
restart box(important)
