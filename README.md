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
Anaconda is a popular open-source platform and distribution for Python, simplifying data science, machine learning, and AI by bundling essential tools like the conda package manager, Jupyter Notebooks, and hundreds of pre-installed libraries, making it easy to manage environments, install packages, and deploy projects
installation:
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
confirm in /home/[user]/anaconda3 

Type YES and press Enter to have Anaconda initialize automatically at startup or type NO if you know what you are doing and if you prefer to activate it manually later.

### Step 2: Initialize Anaconda
If you had installed using the interactive mode and had entered NO to auto-initialization, to initialize Anaconda, run:
source /home/[user]/anaconda3/bin/activate

After activating, run the following to add the shell functions:

```
conda init
```
With the installation and activation complete, the base environment will automatically activate each time you open a new terminal. If you prefer not to have the base environment activated by default, you can disable this behavior by running:


```
conda config --set auto_activate_base False
```
After doing this, Conda won’t automatically activate the base environment when you open a new terminal. To use Conda, you’ll need to manually activate an environment by running 

```
conda activate
```

### Step 3: Verify installation
Verify the installation by checking its complete information using:
```
conda info
```




