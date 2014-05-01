# SaaS Day 1
This project is for a PBL lecture course about cloud computing at the University of Tokyo.

## Source code list


## Procedure log
    $ rails new myapp -d mysql


### Install RVM (See: http://rvm.io/rvm/install)
    $ curl -L https://get.rvm.io | bash -s stable
    $ source ~/.rvm/scripts/rvm
    * add "source ~/.rvm/scripts/rvm" to "~/.bashrc"
    $ rvm requirements

    $ rvm install ruby
    $ rvm use ruby --default
    $ rvm rubygems current
    $ gem install rails
    $ gem install bundler

### Install Open CV
    $ sudo apt-get install cmake build-essential

    * Download a up-to-date package from http://opencv.org
    $ unzip opencv-x.x.x.zip
    $ cd opencv-x.x.x
    $ mkdir release
    $ cd release
    $ cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/opt/local ..
    $ make
    $ sudo make install
    $ gem install ruby-opencv -- --with-opencv-dir=/opt/local



