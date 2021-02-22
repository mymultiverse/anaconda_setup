# anaconda_setup
Anaconda Setup on Ubuntu 20

Anaconda Navigator GUI
```
sudo apt install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
```
Get the installer script
```
wget -P /tmp https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh
```
Run installation
```
bash /tmp/Anaconda3-2020.02-Linux-x86_64.sh
```

Running and Creating Envinronment
```
source ~/.bashrc
conda create -n env_name python=3.8
```
Stop default activation of base env
```
conda config --set auto_activate_base False
```
Ref:
1. https://docs.anaconda.com/anaconda/install/linux/
2. https://linuxize.com/post/how-to-install-anaconda-on-ubuntu-20-04/
