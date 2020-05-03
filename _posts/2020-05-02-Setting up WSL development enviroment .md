## Basic settings
### Install WSL
  1. Press Win key, search for *Turn windows feature on or off* 
  2. In the opened dialogue, check *virtual machine* and *windows subsystem for Linux* options, select restart later
  3. Open *Microsoft Store*, search *Linux*, install *Ubuntu*, restart computer

  ![WSL](/assets/wsl-1.gif)

###  Basic Packages to be installed under Linux
  * Open Ubuntu app form start menu, Set your user name and password
  * update system with command
    
    `sudo apt-get install update` 

  * install pip3 
    
    `sudo apt-get install python3-pip`

  * install pytorch
    
    - go to [pytorch website](https://pytorch.org/get-started/locally/) find the right command to install pytorch  

    `sudo pip3 install pytorch`

    ![pytorch](/assets/pytorch.PNG)
    
  * install other python packages
    
    `sudo pip3 install matplotlib` 
    
    `sudo pip3 install pandas`

### Install VSCode

- google and install VSCode
- VScode automatacly recoganize the file type and suggest the right plugin to install
- Remote WSL plugin 
  
