# Planta Maize Disease 
This project compares multiple object detection models and uses them to detect symptoms of Northern Leaf Blight in maize
![corn](https://user-images.githubusercontent.com/37023871/124835716-c2e30380-df4f-11eb-9c97-b85b130b11c9.jpeg)

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
Ensure to download the handheld images and annotations from
https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-018-3548-6/tables/1
Move the annotations_handheld.csv and rename the handheld images folder to `original_images`

Open the jupyer notebook by running and run the notebooks according to the model names
```bash
jupyter lab
```
