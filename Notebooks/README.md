### Getting Started

#### Creating a virtual env

py -m venv .venv --prompt Notebooks

#### Activate virtual environment and upgrade pip
.venv\Scripts\activate
python -m pip install pip --upgrade

#### Install pytorch, this is for the cuda version 12.8

pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128

#### Install everything else

pip install -r requirements.txt


##### Now that everything is installed you can run jupyter lab

you always have to activate virtual environment when starting before you can run jupyter lab

.venv\Scripts\activate

jupyter lab


