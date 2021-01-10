# activdre
Driver for promethean digital boards to use in linux system with kernel 5.x and conflict witl libcurl3 and libcurl4.

An application for <b>linux</b>, to run drivers/software for old digital boards <b>"SmartBoard"</b> in new <b>Ubuntu</b> based distros. (Bionic and focal based systems). It downloads a <b>docker image</b>, installs dependencies and executes the drivers/software. The aplication run at every startup.

### Linux compatible systems:

+ Ubuntu Focal and Bionic with kernel 5.X
+ Linux Mint based on Ubuntu Focal and Bionic with kernel 5.X

## USAGE

    sudo apt-get update -y
    
    sudo apt-get install git -y

    git clone https://github.com/aosucas499/activdre.git

    cd activdre
    
    chmod +x install

    ./install
    
    sudo reboot (Reboot the system - Reiniciar el sistema)
