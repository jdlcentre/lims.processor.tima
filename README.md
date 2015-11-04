# lims.processor.tima
TESCAN Tima Processor for LIMS

CentOS:

sudo yum groupinstall 'Development Tools'
sudo yum install epel-release
sudo yum install python-pip python-devel libjpeg-devel zlib-devel freetype-devel postgresql-devel
sudo pip install pillow postgres numpy

Debian:

sudo apt-get install libfreetype6-dev postgresql-server-dev-9.4  (this is needed to build the postgres library for python)
sudo ln -s /usr/lib/x86_64-linux-gnu/libfreetype.so /usr/lib
sudo pip install pillow postgres numpy

Either a folder or symlink at mindif_import/ddfe
