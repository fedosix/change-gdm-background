# change-gdm-background
change-gdm-background for Ubuntu 22.10

How to install 

1. First, you will need to install libglib2.0-dev-bin : sudo apt install libglib2.0-dev-bin
2. Install wget : sudo apt install wget 
4. create tmp folder : cd & mkdir tmp && cd ~/tmp 
5. Download scritp : download script :  wget https://raw.githubusercontent.com/fedosix/change-gdm-background/main/change-gdm-background
6. Set it as an executable : chmod +x change-gdm-background
7. Run the script with root privileges such as : sudo ./ubuntu-gdm-set-background --image path to img (sudo ./ubuntu-gdm-set-background --image /home/id/Downloads/wallhaven-x8ye3z.jpg)
