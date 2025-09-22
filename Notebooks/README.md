###Getting Started

####Creating a virtual env

py -m venv .venv
.venv\Scripts\activate

####Install pytorch, this is for the cuda version 12.8

pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128

####Install everything else

pip install -r requirements.txt

