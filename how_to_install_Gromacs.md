# sudo apt-get update
# sudo apt-get upgrade
# sudo apt-get build-essential
# sudo apt-get install cmake

http://www.gromacs.org/Downloads   : where you download Gromacs (5.1.4)

# tar xfz gromacs-5.1.4.tar.gz     : to untar Gromacs in related directory

# cd gromacs-5.1.4
# mkdir build
# cd build
# cmake .. -DGMX_BUILD_OWN_FFTW=ON -DREGRESSIONTEST_DOWNLOAD=ON
# make
# make check
# sudo make install

>source /usr/local/gromacs/bin/GMXRC  must add up this line to the very end of .bashrc file

>nano ~/.bashrc                       : then press ctrl+x and then Y