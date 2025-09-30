# **Getting Started**

# Requirements
- - - 
We will be using Windows 11 64 bit edition, Cuda 12.8 with Nvidia 3060 12 gig TI
I will make an effort to test and verify mosst things will run on CPU though will want to have a minimum of 16 gigs of RAM

We will be installing
 - Python 3.12
 - Git

First open a command prompt by clicking start button and typing cmd and enter then

# Install Python
- - - 

winget install Python.Python.312

# Install Git

winget install Git.Git

# Make sure have Nvidia drivers and Cuda 12.8 

- **For Drivers** https://www.nvidia.com/en-us/software/nvidia-app/ 
- **Cuda 12.8.1** https://developer.nvidia.com/cuda-12-8-1-download-archive?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_network


# First Steps
- - - 

*Most projects will start same way*

mkdir (projectname)

cd (projectname)

Py -3.12 -m venv .venv --prompt (projectname)

.venv\Scripts\activate

python pip install pip --upgrade

pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128

*or for cpu version without cuda*

pip3 install torch torchvision


*Now you have an environment ready to go, install additional packages with pip and start coding*












