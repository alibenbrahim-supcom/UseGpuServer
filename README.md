# UseGpuServer
how to use our Linux server With GPU
IP address , login and password sent by mail
Our SUP'COM Server with GPU is an UBUNTU Server 22.04 , 96G RAM, 1T Disk, NVIDIA A40 GPU (48GVRAM)

This readme will show you how to install and run ollama, python, pytorch in your own environment 
Also inform you all models and applications installed for you 

# Install and Use pytorch
several methods exists to install **pytorch**  
we show here one method works and tested .  

## Install Anaconda

be shure you are in your root directory and create a tmp folder

```
cd ~
mkdir tmp
cd tmp
```

copy paste if you do not find the ~ on your keyboard

### Step 1: copy the Anaconda installer and install

```
cp /home/ftp/anaconda3/anaconda.sh .
bash anaconda.sh
```
accept the licence terms 
confirm in /home/<user>/anaconda3 

Type YES and press Enter to have Anaconda initialize automatically at startup or type NO if you know what you are doing and if you prefer to activate it manually later.

### Step 2: Initialize Anaconda
If you had installed using the interactive mode and had entered NO to auto-initialization, to initialize Anaconda, run:
source /home/"<user>"/anaconda3/bin/activate

After activating, run the following to add the shell functions:

```
conda init
```



