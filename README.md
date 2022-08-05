## Facial Image Emotion Recognition Based On Cartoonized Features (FER-Cartoon)

This is the final project for SJTU JI ECE4880J.


### Installation
To use this repo, create a conda environment using `environment.yml` or `requirements.txt`

```
# from environment.yml (recommended)
conda env create -f environment.yml

# from requirements.txt
conda create --name <env> --file requirements.txt
```
The cartoonized fer2013 dataset are in the following folder: 

`datasets/fer2013/fer2013_cartoonized.csv` 

### Usage

To train your own version of our network, run the following

```
python train.py network=vgg name=my_vgg
```
To change the default parameters, you may also add arguments such as `bs=128` or `lr=0.1`. For more details, please refer to `utils/hparams.py`

### Testing

Please refer to `notebooks/Evaluation.ipynb` for testing.