# Planta Maize Disease 
This project compares object detection models using Detectron2 on a dataset of corn for detecting Planta Maize disease

# Installation
Install the correct version of detectron2 based on your CUDA version
Run `nvidia-smi` to check your CUDA version
Then install detectron2 following the instructions in this link
https://detectron2.readthedocs.io/en/latest/tutorials/install.html

Also ensure the correct version of pytorch is installed according to your CUDA version
https://pytorch.org/get-started/previous-versions/

Ensure pipenv is intsalled
```bash
pip install pipenv
```

Then install the packages by running
```bash
pipenv install
```
to install the required packages.

Then activate the shell
```bash
pipenv shell
```

Ensure everything is installed correctly and uses consistent CUDA versions by checking
```bash
python -m detectron2.utils.collect_env
```

# Usage
Ensure to download the images and annotations from
https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-018-3548-6/tables/1


Open the jupyer notebook by running and run the notebooks according to the model names
```bash
jupyer lab
```

